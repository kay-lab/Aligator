# Aligator
Automated Ligator = Aligator

Version 1.0

This script takes all FASTA .txt files within a directory and predicts optimal ligation
strategies. The top 1000 strategies (based on 5 different scoring functions) are
shown within the Aligator analysis Excel file for each protein. All strategies are placed
within text files in case the user wants to view them. All files listing all segments
used to calculate the ligation strategies, along with their solubility scores, for
the entire folder of FASTA .txt files is also shown within a separate text file.

This script is compatible with Python 2.7. The user must have the openpyxl and joblib
Python libraries installed in order for Aligator to work.
