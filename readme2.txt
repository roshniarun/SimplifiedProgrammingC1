Name - Roshni.A.
USN - 1PI12IS089
CSV FILE: countries.csv
Question No - 5
Question StatementYou are given a .csv file which has been written in the following format
COUNTRY,CAPITAL,POPULATION

Write a program which reads data from the .csv file and populates it into a .txt file in the form of
sentences like:

The capital of <COUNTRY>is <CAPITAL>with a population of <POPULATION>.

This application has a new requirement to display the most spoken language of that country. Add
another column called LANGUAGE in the csv file such that the order looks like this:

COUNTRY,CAPITAL,POPULATION,LANGUAGE
and it should populate into the .txt file should be in the form of the following sentences:
The capital of <COUNTRY> is <CAPITAL> with a population of <POPULATION> and the
language spoken is <LANGUAGE> 

assign3.py contains the actual working code. It has 2 files. a log file and an output file. 
It has a dict_reader that will read from the csv file and in the main file it will use command line arguments.

Country.csv - This file consists of a collection of four columns (country,capital,population and language) of various countries

EXECUTION OF THE PROGRAM:  python3 asn2.py -f <file_name> -l <logfile_name>

CHALLENGES FACED: A tough time using Github! Had a lot of problems.The assignment was not tough but uploading the assignment was
tough!
