# Software Construction – Lab Task 04

## Data Types, Mutability, and Collections

**University:** University of Engineering and Technology, Abbottabad Campus

**Class:** 5th Semester Software Engineering

**Subject:** Software Construction

**Date:** 08 September 2026

## Objective

Applying concepts of mutability, interface implementations (List, Map, Set), and safe iterator traversal using Java Collections.

## Lab Tasks

### Task 1 – String vs StringBuilder

Implemented `StringPerformance.java` to compare `String` concatenation with `StringBuilder.append()` and measured their execution time for `n = 10000`.

### Task 2 – Safe Collection Modification

Implemented `CourseManager.java` to demonstrate `ConcurrentModificationException` and safely remove subjects using an `Iterator`.


### Task 3 – HashMap

Implemented `TreasureMap.java` using `HashMap`. The value of `"palm"` was updated and the total treasure value was calculated.



### Task 4 – Unmodifiable List

Implemented `Zoo.java` using `Collections.unmodifiableList()`. Attempting to add an animal produces `UnsupportedOperationException`.

## Homework

### Homework 1 – StudentDirectory

Implemented `StudentDirectory.java` using `Map<Integer, String>` and returned an unmodifiable set of student IDs using `Collections.unmodifiableSet()`.

### Homework 2 – Immutable Point

Implemented an immutable `Point` class using a `final` class, `final` fields, a constructor, and getter methods without setters.


## How to Run

The project was developed in **Apache NetBeans**.

1. Open the project in NetBeans.
2. Right-click the required Java file.
3. Select **Run File**.
4. For JUnit tests, right-click the test file and select **Test File**.

