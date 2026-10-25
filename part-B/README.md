# Final MiniBank Project

Main file: `MiniBank.java`

## Compile and run (JDK 17+)

bash
javac MiniBank.java
java MiniBank


The program saves account data to `minibank-data.dat` when **Save and Exit** is selected and loads it on the next start.

## Features
- Open account, deposit, withdraw, transfer
- Account statement, list, and report
- Generic repository using `@Id` reflection
- Custom bank exceptions and validation
- Concurrent deposits using a fixed thread pool
- Save/load persistence and a save/load test method

This is a single-file submission version, so all classes are in `MiniBank.java` rather than separate Java package files.

