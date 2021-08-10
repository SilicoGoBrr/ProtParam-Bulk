# ProtParam-Bulk

This simple program takes advatage from Bio package and SeqUtils to retrieve basic information about a protein sequence query in FASTA. It is particularly useful when 
working with lots of sequences.

It will retrieve information from any fasta file as provided by NCBI as long as it is protein sequence. This program can not perform proper analysis on any DNA or RNA sequences
of any type.

The code is written in python 3.9. It has not been tested in any other version. Compatibility is not ensured.

If familiar with SeqUtils users can easily expand this code to aquire other important information from the databases
For further documentation about the package visit:

https://biopython.org/docs/1.75/api/Bio.SeqUtils.ProtParam.html

The output of the program is a .txt file which is actually a .csv file. It can be easily opened in excel and transformed in a table using PowerQuery. 
Notice that Excel's PowerQuery tends to change data type information. If your program is trying to do this just DENY or CANCEL that change. OTHERWISE THIS MIGHT CAUSE TROUBLE
WITH FLOAT NUMBERS.

Feel free to comment or report any experiences/issues/bugs with the software.
