All files expected to be in the same directory. It is assumed that Notepad++ is installed. More details at end.

Files BEFORE running include:
12 - .in
12 - .out
README.txt
DELETE.bat
RUN_ALL.bat

Solutions are labeled as "c2-fcfs_sol.out"

How to Use:
Place student's python file into folder. Rename to "scheduler-gpt.py" if it isn't already.
Double click RUN_ALL.bat to test all .in files with the .py file and produce respective .out files.
Notepad++ opens with all _sol.out and generated .out files. Any files not generated will not be opened.
After reviewing, then double click DELETE.bat to delete all generated .out files and scheduler-gpt.py.

Expected results:
RUN_ALL:
A command window should pop up and each of the scheduler-gpt.py will run for each .in case. The .out files will be generated in the working directory.
Notepad++ will then open each _sol.out and generated.out pair.

If a .out file does not generate, then either the naming convention is wrong for the input file (i.e. the student's code may specify fifo instead of fcfs).
Change the un/commented lines in RUN_ALL as appropriate.

DELETE:
A command window should pop up to delete all generated .out files and the scheduler.ppy file. These will be deleted from the directory.

Notepad++:
Assumed to be installed at "C:\Program Files\Notepad++\notepad++.exe"
Adjust path if installed elsewhere or comment out lines in RUN_ALL.bat.