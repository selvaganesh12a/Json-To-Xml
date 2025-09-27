## JSON to XML Converter Project

This is a simple Java program that converts JSON data to XML format according to a specific set of rules. The program is built using Maven and relies on the `org.json` library for JSON parsing and XML creation. It is designed to be run from the command line.

***

## Building the Project

This project uses **Maven** for build automation. To build the project, you must have Maven installed on your system.

Open a terminal and navigate to the root directory of the project (where this `README` file and the `pom.xml` file are located).

Run the following command to compile the code, run tests, and package it into a single executable JAR file:

`mvn clean package`

Upon successful completion, Maven will create a `target/` directory containing the executable JAR file named `JsonToXml-1.0-SNAPSHOT-jar-with-dependencies.jar`.

***

## Running the Program

The program is run from the command line and requires two arguments: the path to the input JSON file and the path to the output XML file.

**Command Syntax:**
`java -jar target/JsonToXml-1.0-SNAPSHOT-jar-with-dependencies.jar <input_json_file> <output_xml_file>`

**Example:**
`java -jar target/JsonToXml-1.0-SNAPSHOT-jar-with-dependencies.jar jsondata.json output.xml`

If the number of arguments is not exactly two, the program will print a usage message to the console.

***

## Used Libraries

The following open-source library was used in this project:

**`org.json`**: A library for parsing and manipulating JSON data.
    **URL**: `https://mvnrepository.com/artifact/org.json/json` 

***

## Test and Auxiliary Files

**`jsondata.json`**: This file is an example of a valid JSON input file that can be used to test the program's functionality.
