# TEJAS Flashcards Program

## Flashcards Program for the Tejas Club
Originally developed 2001, Logan Kunitz

Updated 2022, Logan Kunitz

### Overview

The Flashcards program allows you to define a seat-map for the section in the stadium that will be used in the stadium. It then allows you to draw 'stunts' over the seat map using the common flashcards colors. Up to 6 "stunts" are supported by the application. Once all of the stunts are defined, the application will export the seat information along with the flashcard colors for each of the stunts to either a .csv file or an MS access database. Once in these locations, labels can be created for all of the flashcards.

### Installation

Run the installer, which will put the application in the program folders location. Launch the application using "Flashcards.exe".

If you are planning to use the MS Access database, you will also need to install this application:
https://www.microsoft.com/en-us/download/details.aspx?id=13255


### Help for the Seat Information Files

These are comma-delimited spreadsheet files with the ".sts.csv" extension that must be created before running the flashcards program. An example file is included in the same folder as the executable. You can open these files from excel, then follow the instructions in the file. **Do not alter the structure of the header rows and first couple of columns.**

The layout of the file should represent the seat layout in the flashcards section. The first column represents the row number, and the header row represents the section that all the seats below it are a part of. Each individual seat number is listed in it's appropriate spot. A negative number, such as "-1", in the file corresponds to a seat that will not be used when creating the labels for the flashcards. The file "flashcards_original.sts" contains all of the information about our section as of 2002. "flashcard_seats_example.sts.csv" is an example demonstrating how to create the file.

### Help for the Flashcards Program

First, select the seat layout that you would like to use for all the stunts. Then, select how many stunts you would like to create. After clicking OK, draw your stunts or load them from a previous file. If you wish, you can save a stunt as a ".stn.csv" file for future use. An example file "texas_flag_example.stn.csv" is included with the program. Once you are done drawing **ALL** of the stunts, click the "Create CSV File" or "Create Access Database" button. This will give you options for saving the flashcards information to either a table in the Flashcards.mdb database, or in a .csv file. For the MDB file, you have the option of either creating a new table, or overwriting an existing table. When creating a new table, there cannot be any spaces in the table name. Once the files are created, you can proceed to creating labels.

### About the Database
The flashcards database "flashcards.mdb" will be located in the root folder of the application, but must stay there for the program to work properly.



### Using Microsoft Access to Create the Labels
Note: these instructions require Microsoft Access to be installed. They were also written based on the 2001 version of microsoft access, and I have not figured out yet how to make this work in the latest version.
- Open Microsoft Access, and then open the existing flashcards database which should be located at
```<application root>\flashcards.mdb"```. 
- The table you created in the previous step should be located under ```Tables```. Open
it up to make sure all the information is there.
- To make labels, click on "reports," and then click on the "new" button at the top which will give several options 
for report types. One option should be "Label wizard," and if you click on this option it will step you through 
the process of make labels with the table that you just created.

YIT,
Logan Kunitz