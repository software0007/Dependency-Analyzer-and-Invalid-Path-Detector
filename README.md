# Dependency-Analyzer-and-Invalid-Path-Detector
Dependency Analyzer and Invalid Path Detector is a Python-based tool that analyzes SQL dependencies in .jsp files and identifies invalid data flow paths. It features both syntax and semantic analysis using different abstract domains and includes a GUI built using Tkinter.

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
1. Initial Interface: Browse for .jsp and database files.

![Screenshot 2025-04-09 183718](https://github.com/user-attachments/assets/6c6f7fbd-237f-4119-9993-285d5db6e5f9)
![Screenshot 2025-04-09 183747](https://github.com/user-attachments/assets/24fa4696-e81c-4ad2-87b7-63fd5e1f66b0)




2. Input Files Selected

Example: LedgerRecord.jsp and LedgerDatabase.

![Screenshot 2025-04-09 183906](https://github.com/user-attachments/assets/20a2b296-2553-42e8-9975-d4e6efcdec9c)





3. Syntax-Based Dependency Analysis

Displays number of SQL statements, dependencies, paths, and analysis time.
![Screenshot 2025-04-09 183925](https://github.com/user-attachments/assets/d15945c0-a9ee-45c8-b0dc-459317adeeb5)




4. Semantic Option Selected
   
![Screenshot 2025-04-09 184351](https://github.com/user-attachments/assets/584b8664-c0f5-4800-86f5-fe57b63dc1fb)


5.User can choose between Polyhedron and Interval Domain.

![Screenshot 2025-04-09 185510](https://github.com/user-attachments/assets/5ddf31b6-4ff7-4865-8390-9c9024fe25e2)





6. Polyhedra-Based Analysis Output

Includes direct/indirect dependencies, false dependencies, and path info.

![Screenshot 2025-04-09 190106](https://github.com/user-attachments/assets/83a7bb3e-ce3e-4464-ac54-366904d243b0)



7. Interval Domain Output

Displays results for interval-based analysis.

![Screenshot 2025-04-09 190234](https://github.com/user-attachments/assets/449cd2d3-0554-4d17-8f99-34a3f3d82537)
![Screenshot 2025-04-09 190242](https://github.com/user-attachments/assets/d3a85ca5-001a-41a9-87f0-d6d45bcaf77f)




🛠 Requirements
Python 3.x

Tkinter (usually preinstalled)

RAM: 4 GB or higher

📌 Note
Only supports .jsp files using numerical data in SQL queries.

Best suited for database-driven JSP applications.

