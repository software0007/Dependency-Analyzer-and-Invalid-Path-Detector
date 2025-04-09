# Dependency-Analyzer-and-Invalid-Path-Detector
Dependency Analyzer and Invalid Path Detector
SemDDA is a Python-based tool that analyzes SQL dependencies in .jsp files and identifies invalid data flow paths. It features both syntax and semantic analysis using different abstract domains and includes a GUI built using Tkinter.

🚀 Features
Parses .jsp files and identifies SQL statements.

Detects direct and indirect dependencies between attributes.
Performs Syntactic analysis
Performs semantic analysis using:

Interval Domain

Polyhedra Domain

Provides GUI-based interaction for easy use.

Highlights:

Valid and invalid paths

Execution time

🧠 Under the Hood
Modules
Preprocessor: Adds line numbers, counts SQL statements, and ignores comments.

ExtractInfo: Gathers variable usage and control structures.

Dependency Analyzer: Computes syntax-based dependencies.

Abstraction: Performs semantic analysis using interval or polyhedra.

🖥 GUI Overview
Built with Python Tkinter, the GUI guides users through every step of dependency detection.

GUI Screenshots
1. Initial Interface

Browse for .jsp and database files.
![Screenshot 2025-04-09 183718](https://github.com/user-attachments/assets/6c6f7fbd-237f-4119-9993-285d5db6e5f9)



2. Input Files Selected

Example: LedgerRecord.jsp and LedgerDatabase.




3. Syntax-Based Dependency Analysis

Displays number of SQL statements, dependencies, paths, and analysis time.


4. Semantic Option Selected

User can choose between Polyhedron and Interval Domain.


5. Polyhedra-Based Analysis Output

Includes direct/indirect dependencies, false dependencies, and path info.


6. Interval Domain Output

Displays results for interval-based analysis.
