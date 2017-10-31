# Aligator
Automated Ligator = Aligator

Version 1.1.1

***To download the new Aligator executable, please navigate to the "Releases" tab and
download the compressed executable folder for your computer's operating system.***

This script takes all FASTA .txt files within a directory and predicts optimal total 
chemical ligation strategies. The top 1000 strategies (based on 5 scoring functions) are
shown within the Aligator analysis Excel file for each protein. All strategies are placed
within text files, in case the user wants to view them. All viable peptide segments
used to calculate the ligation strategies, along with their solubility scores, for
each protein are shown within the Viable Segment Lists Excel file. The Aligator Run
Information document shows all user inputs, statistics, and run time for the
program. All output files are stored within a folder that is timestamped based on when
Aligator was launched.

Please read the "Aligator Documentation and Installation" PDF before using Aligator v1.1.1
for the first time.

Aligator is now available as an executable for both Mac and Windows! Please note:
the Mac executable was prepared on OS X 10.8 (Mountain Lion), and may only work on
OS X versions 10.8 and above. The Windows executable was prepared on Windows 7, and may only
work on Windows 7 and above. Users do not need to install anything to have the Aligator
executables function properly on their computer.

Version 1.1.1 repaired a bug that occassionally caused segments larger than the user's defined
maximum segment length to remain as viable segments.

This script is compatible with Python 2.7. If the user is working with the source code, the 
openpyxl and joblib Python libraries must be installed in order for Aligator to work.
