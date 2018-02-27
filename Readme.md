## Python scripts to load GNAF to a postgres database using psycogp2
#### update date: 27/02/2018
#### author: Jubert Roldan

note: once the full folder has been downloaded, user must modify the file locations.
preferred to create a main folder with 3 folders containg the following:

1. data
2. output
3. scripts

the script is pretty straightforward and runs at a decent speed.my main folder is called 

gnaf_loader/

with 3 folders contained

gnaf_loader/data -> this is where the usual GNAF file will be uncompressed after downloading from data.gov.au
gnaf_loader/output - this is where python will write the csv output.
gnaf_loader/scripts -> this is where the scripts are contained.


in order to run all python scripts to read all the tables simply run
gnaf_loader/scripts/GNAF_SEQUENCE.py using the python command python GNAF_SEQUENCE.py.


hope this helps! 


