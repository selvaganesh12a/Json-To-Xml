## JSON to XML Converter Project

[cite_start]This is a simple Java program that converts JSON data to XML format according to a specific set of rules[cite: 3]. [cite_start]The program is built using Maven and relies on the `org.json` library for JSON parsing and XML creation[cite: 3]. [cite_start]It is designed to be run from the command line[cite: 3].

***

## Building the Project

[cite_start]This project uses **Maven** for build automation[cite: 3]. [cite_start]To build the project, you must have Maven installed on your system[cite: 3].

[cite_start]Open a terminal and navigate to the root directory of the project (where this `README` file and the `pom.xml` file are located)[cite: 3].

[cite_start]Run the following command to compile the code, run tests, and package it into a single executable JAR file[cite: 3]:

`mvn clean package`

[cite_start]Upon successful completion, Maven will create a `target/` directory containing the executable JAR file named `JsonToXml-1.0-SNAPSHOT-jar-with-dependencies.jar`[cite: 3].

***

## Running the Program

[cite_start]The program is run from the command line and requires two arguments: the path to the input JSON file and the path to the output XML file[cite: 3].

**Command Syntax:**
`java -jar target/JsonToXml-1.0-SNAPSHOT-jar-with-dependencies.jar <input_json_file> <output_xml_file>`

**Example:**
`java -jar target/JsonToXml-1.0-SNAPSHOT-jar-with-dependencies.jar jsondata.json output.xml`

[cite_start]If the number of arguments is not exactly two, the program will print a usage message to the console[cite: 3].

***

## Used Libraries

[cite_start]The following open-source library was used in this project[cite: 3]:

* [cite_start]**`org.json`**: A library for parsing and manipulating JSON data[cite: 3].
    * [cite_start]**URL**: `https://mvnrepository.com/artifact/org.json/json` [cite: 3]

***

## Test and Auxiliary Files

* [cite_start]**`jsondata.json`**: This file is an example of a valid JSON input file that can be used to test the program's functionality[cite: 3].
