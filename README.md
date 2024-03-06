# LibreOffice Contributions Portfolio

This repository serves as a overview of the contributions 
I have made to the LibreOffice project. LibreOffice uses a different 
version control system, the links below will direct you to the merged commits 
for each contribution.

## Contributions

### Fix 1: https://gerrit.libreoffice.org/c/core/+/162678

Summary: The objective of this contribution was to enhance the header file structure 
by replacing include guards with the modern `#pragma once` directive. 
The goal was to improve code readability while simplifying maintenance.

### Fix 2: https://gerrit.libreoffice.org/c/core/+/162950

Summary: This contribution replaced existing index based for loops with C++11's
range-based alternatives where applicable. This made the codebase more 
concise and easier to understand.

### Fix 3: https://gerrit.libreoffice.org/c/core/+/163927

Summary: This commit involves migrating from the `SAL_N_ELEMENTS()` macro to using
the built in C++ `std::size()` function that calculates the number 
of elements in an array at compile time. This transition aims to modernize
LibreOffice's code base with modern C++ standards.
