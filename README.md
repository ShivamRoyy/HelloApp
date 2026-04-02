# HelloApp

A Java Maven project that progressively builds a greeting application across 7 Use Cases (UC1–UC7).

**Author:** Shivam Kumar

---

## Use Cases

| UC | Branch | Description |
|----|--------|-------------|
| UC1 | `feature/UC1-display-hello` | Print "Hello, World!" |
| UC2 | `feature/UC2-display-name` | Greet by name (default to World) |
| UC3 | `feature/UC3-display-name-default` | Explicit default with if-else |
| UC4 | `feature/UC4-display-multiple-names` | Greet multiple names (indexed for loop) |
| UC5 | `feature/UC5-enhanced-for-loop` | Greet multiple names (enhanced for-each) |
| UC6 | `feature/UC6-substring-method` | Join names using StringBuilder + substring |
| UC7 | `feature/UC7-string-join` | Join names using String.join() |

---

## Build & Run

```bash
mvn compile
mvn exec:java -Dexec.mainClass="HelloApp"
mvn exec:java -Dexec.mainClass="HelloApp" -Dexec.args="Alice Bob Charlie"
```

---

## Example Output

```
Hello, World!
Hello, Alice, Bob, Charlie!
```
