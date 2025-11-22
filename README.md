AlgorithmToolkit – Mini Project 3

This project contains a small Java utility library that includes basic algorithms and data-structure implementations. It was created as part of Mini Project 3 for the Data Structures & Algorithms course.

📌 Features
1. SortingUtil

Implements four sorting algorithms:

Bubble Sort

Insertion Sort

Merge Sort

Quick Sort

2. SearchUtil

Two search methods:

Linear Search

Binary Search (requires sorted array)

3. CollectionUtil

Generic data-structure utilities:

Stack<T>

Queue<T>

4. AnalysisUtil

Simple benchmarking function to measure algorithm execution time.

📁 Project Structure
com.training.toolkit
 ├── SortingUtil.java
 ├── SearchUtil.java
 ├── CollectionUtil.java
 └── AnalysisUtil.java

🧪 Testing

Includes JUnit test cases for:

Sorting algorithms

Search algorithms

Stack & Queue

Benchmarking tool

Run all tests using:

mvn test

▶ Example
int[] arr = {5, 2, 8};

SortingUtil.quickSort(arr);
int index = SearchUtil.binarySearch(arr, 5);

System.out.println(Arrays.toString(arr)); // [2, 5, 8]
System.out.println("Index: " + index);

✔ Maven Dependencies

Add to pom.xml:

JUnit
<dependency>
    <groupId>org.junit.jupiter</groupId>
    <artifactId>junit-jupiter</artifactId>
    <version>5.9.0</version>
    <scope>test</scope>
</dependency>

Servlet API (if using in a web project)
<dependency>
    <groupId>jakarta.servlet</groupId>
    <artifactId>jakarta.servlet-api</artifactId>
    <version>5.0.0</version>
    <scope>provided</scope>
</dependency>

👨‍💻 Author

Abdullah
Mini Project 3 – Algorithm Toolkit
