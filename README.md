# Unit 1 Java Programming Project

This project is designed for Mr. Hare's APCS-A, focusing on Unit 1 concepts such as primitive data types, variable declaration, operators, and casting. The project includes a set of methods that students need to implement, along with unit tests to verify their functionality.

## Project Structure

- **`Unit1.java`**: Contains method headers and task descriptions. Students are required to implement the method bodies.
- **`Unit1Test.java`**: JUnit test cases for each method in `Unit1.java`. These tests validate the correctness of the implemented methods.
- **`pom.xml`**: Maven configuration file that manages dependencies and plugins required to build and run the project.

## Prerequisites

- Java 17 (or compatible version)
- Maven 3.x

## Getting Started

### Accept the Project

Use the link found in Google Classroom to accept the assignment in GitHub Classroom.

### Clone the Repository

Clone this repository to your local machine using GitHub Desktop.

### Run Tests

Run the JUnit tests to verify your implementations.

## Method Descriptions

Students need to implement the following methods in `Unit1.java`:

1. **`addIntegers(int a, int b)`**: Returns the sum of two integers.
2. **`castDoubleToInt(double value)`**: Converts a double to an integer by casting.
3. **`isTrue(boolean value)`**: Returns `true` if the boolean parameter is true, otherwise returns `false`.
4. **`maxValueMinusOne()`**: Returns the maximum integer value (`Integer.MAX_VALUE`) minus one.
5. **`multiplyIntAndDouble(int a, double b)`**: Returns the product of an integer and a double as a double.

## Common Mistakes to Avoid

- Forgetting that Java is case-sensitive (e.g., `myScore` is not the same as `myscore`).
- Forgetting to specify the type when declaring a variable (e.g., using `name = value;` instead of `type name = value;`).
- Using a variable name without declaring the variable.
- Using the wrong name for a variable (e.g., declaring it as `studentTotal` but using `total` later).
- Using the wrong type for a variable, especially when using integer types in calculations that yield fractional results. Either cast one value to double or use a double variable.
- Using `==` to compare double values instead of testing if the absolute value of the difference between the values is below a certain threshold.
- Assuming 0 is smaller than other int values; use `Integer.MIN_VALUE` for the smallest possible int value.

## Contributing

Feel free to submit issues or pull requests if you find bugs or have suggestions for improvement.

## Contact

For any questions, please contact [Mr. Hare](mailto:kevin.hare@sduhsd.net).
