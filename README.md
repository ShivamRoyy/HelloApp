# HelloApp

Hello App starts with Hello World, progresses to displaying a user name, then names from command-line args and standard input. It then manages names in a collection with list/remove options, refactors into methods and classes, adds persistence across runs, and finally displays names in banner format.

## Use Case Roadmap

1. UC1: Print a basic greeting in the console.
2. UC2: Accept one name via command-line input and greet that user.
3. UC3: Support optional argument handling with a default greeting path.
4. UC4: Handle multiple command-line names in one execution.
5. UC5: Read a single name from standard input.
6. UC6: Read and process multiple names from standard input.
7. UC7: Store entered names in memory and list them on request.
8. UC8: Add removal support for stored names.
9. UC9: Extract input-processing logic into dedicated methods.
10. UC10: Move name-management responsibilities into a separate class.
11. UC11: Persist names to storage and reload them across runs.
12. UC12: Render greeting text in banner-style output for enhanced display.

## How to Run

```bash
# Compile
mvn compile

# Run
mvn exec:java

# Run with a specific main class
mvn exec:java -Dexec.mainClass="HelloApp"
```
