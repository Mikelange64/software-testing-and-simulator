# Robot Motion Simulator

## Project Overview
A Java Maven application that simulates a robot moving on an N x N floor. The robot accepts commands to move, rotate, change pen state, print floor output, and replay history, while safely handling boundaries and invalid input.

##  Commands
| Command | Description |
|---------|-------------|
| `U` | Pen up |
| `D` | Pen down |
| `R` | Turn right |
| `L` | Turn left |
| `M s` | Move forward s spaces |
| `P` | Print the floor |
| `C` | Show current position and status |
| `Q` | Quit |
| `I n` | Initialize n×n floor |
| `H` | Replay command history |


## Requirements
- Java JDK 8 or higher
- Maven 3.x
- Git 

## Project Structure
```text
.
|- pom.xml                          # Maven build configuration
|- src/
|  |- main/
|  |  |- java/
|  |  |  |- org/
|  |  |  |  |- example/
|  |  |  |  |  |- Main.java        # Robot command logic
|  |  |- resources/
|  |- test/
|  |  |- java/
|  |  |  |- org/
|  |  |  |  |- example/
|  |  |  |  |  |- RobotParameterizedTest.java  # Parameterized test suite
|- target/                          # Build outputs, reports, compiled classes
```

## Quick Start
1. Open the project folder in terminal.
2. Run `mvn clean compile` to build.
3. Run `mvn test` to execute tests.
4. Run `mvn jacoco:report` to generate coverage report.

## Commands
- `mvn clean compile`
- `mvn test`
- `mvn jacoco:report`
- `mvn -q test`

## Tests
- Total tests: 78
- Pass rate: 100% (78 passed, 0 failed, 0 errors, 0 skipped)
- Coverage rate (JaCoCo line coverage): 85.81%

## Author
- Name: YOGESHWARAN BASKARAN
- Roll Number: 40323964