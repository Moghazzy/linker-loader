Write a program to simulate an absolute Loader for SIC HTE record, and a Linker-Loader HDRTME
record with external symbol table.
Your program should first ask the user if the input file (input.txt file) is a SIC assembly code or SIC/XE
assembly code. Second, read the input file (input.txt file). Third, your program should apply absolute Loader for
SIC assembly or Linker-Loader for SIC/XE assembly.
• For the Absolute Loader (SIC assembly code), your program should:
o Simulate the SIC memory and fill it will the correct values.
o The SIC memory should be presented as GUI interface.
• For the Linker-Loader (SIC/XE assembly code), your program should:
o Generate External Symbol Table for these control sections and save it in (Ext_Sym_Table.txt).
o Simulate the SIC/XE memory and fill it will the correct values.
o Apply modifications (M records)
o The SIC/XE memory should be presented as GUI interface.

Note: In case of SIC assembly code (no control sections only one HTE record) while in SIC/XE (you may have
at least 2 control sections HDRTME records)
Assessment
THE SAME TEAM OF PHASE 1 WILL NOT BE CHANGED. Each team member will be assessed for his
individualwork as well as for the group work. Both members should agree on the programming languages and
code structures to be used. The table below shows the tasks required from each team member. IF YOU ARE
ALONE WITHOUT TEAMMATE, YOU MUST DO BOTH WORK OF STUDENT 1 & 2.
The only bonus is to deliver the project after it is published by 1 week and discuss it. (date to deliver
bonus on classroom to have discussion after it: 12.12.2022 (before 11.59 pm)
Student 1 Student 2
Input Parsing Input Parsing
Absolute Loader (handling HTE records) Linker-Loader (handling HDRTE records)
Presenting memory as GUI (SIC/SIC/XE) Linker-Loader (handling M records)
Report (Documentation) Report (Documentation)
Executable File Executable File
Each team should submit the merged source code and executable files and each student should
submit the individual source code, executable files, and a report that includes:
• example statements on how to use your program (both individual and merged). E.g. for a
python program: python3 code.py --data in.txt
• design issues and sample run
