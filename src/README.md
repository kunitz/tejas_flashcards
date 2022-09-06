# TEJAS Flashcards Program

## Flashcards Program for the Tejas Club
Originally developed 2001, Logan Kunitz
Updated 2022, Logan Kunitz


### Help for the Seat Information Files

These are spreadsheet files with the ".sts" extension that must be created before running the flashcards program. You can open these files from excel by opening as a text file, and then selecting "Tab-Delimited" to represent the data.


The layout of the file should represent the seat layout in the flashcards section. The first column represents the row number, and the first row represents the section that all the seats below it are a part of. Each individual seat number is listed in it's appropriate spot. A negative number, such as "-1", in the file corresponds to a seat that will not be used when creating the labels for the flashcards. The file "flashcards_original.sts" contains all of the information about our section as of 2002. "flashcards.sts" is the reocommended setup for the flashcards section. Many of the outer seats are greyed out to make the section roughly square.

You can edit the Seat Information files from within the program. For minor edits this can be helpful, but a spreadsheet program is probably quicker and easier for large edits.

### Help for the Flashcards Program

First, select the seat layout that you would like to use for all the stunts. Then, select how many stunts you would like to create. After clicking OK, draw your stunts or load them from a previous file. If you wish, you can save a stunt as a ".stn" file for future use. Once you are done drawing ALL of the stunts, click the "finish and create labels" button. This will give you options for saving the flashcards information to a table in Flashcards database. You have the option of either creating a new table, or overwriting an existing table. When creating a new table, there cannot be any spaces in the table name.

### About the Database
The flashcards database "flashcards.mdb" will be located in the root folder of the application, but must stay there for the program to work properly.

This application must be installed for the program to access the database without error:
https://www.microsoft.com/en-us/download/details.aspx?id=13255


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