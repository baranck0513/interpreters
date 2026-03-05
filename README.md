## jlox — Tree-Walk Interpreter (Java)

A fully-featured Lox interpreter implemented in Java using a tree-walk evaluation
strategy. Covers the full language: expressions, statements, variables, control flow,
functions, closures, classes, and inheritance.

**Build:**
```bash
cd jlox
javac -cp src -d out src/com/craftinginterpreters/lox/Lox.java
```

**Run a file:**
```bash
java -cp out com.craftinginterpreters.lox.Lox path/to/script.lox
```

**REPL:**
```bash
java -cp out com.craftinginterpreters.lox.Lox
```

## clox — Bytecode Virtual Machine (C)

A high-performance Lox implementation in C that compiles Lox source directly to
bytecode and executes it on a custom stack-based VM. Features string interning,
a custom hash table, mark-and-sweep garbage collection, and closures via upvalues.

**Build:**
```bash
cd clox
make
```

**Run:**
```bash
./clox path/to/script.lox
```

## Progress

### jlox
- Scanning
- Representing Code
- arsing Expressions
- Evaluating Expressions
- Statements and State
- Control Flow
- Functions
- Resolving and Binding
- Classes
- Inheritance

### clox
- Chunks of Bytecode
- A Virtual Machine
- Scanning On Demand
- Compiling Expressions
- Types of Values
- Strings
- Hash Tables
- Global Variables
- Local Variables
- Jumping Back and Forth
- Calls and Functions
- Closures
- Garbage Collection
- Classes and Instances
- Methods and Initializers
- Superclasses
- Optimization
