# Wikipedia Link Parser

## Introduction
Wikipedia Link Parser is a Java-based console application that takes user input for a start and end Wikipedia page and finds a path between them. It uses the Wikipedia API to fetch links and employs a breadth-first search algorithm to find the connection.

## Features
- Interactive console-based user input for start and end pages.
- Utilizes the Wikipedia API to fetch outgoing links from a page.
- Employs a breadth-first search strategy to find the shortest path between pages.
- Handles parsing and encoding of page titles for API queries.
- Displays a JFrame window with the path and search details upon completion.

## Prerequisites
Before you run the Wikipedia Link Parser, make sure you have the following:
- Java Development Kit (JDK) installed on your system.
- Network access to Wikipedia's API endpoints.

## Installation
No installation is needed. Compile the Java file and run it directly through a Java Runtime Environment.

```shell
javac Main.java
java Main
