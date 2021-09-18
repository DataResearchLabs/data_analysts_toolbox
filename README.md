# Data Analysts' Toolbox - Prototypes

## Overview
Collection of useful data analyst tools to manipulate everything from text files to database systems like MS SQL Server, Oracle, MySQL, or Postgresql. 

Disclaimer:  These tools are all prototyped in Microsoft Access -- I know, groan...but MS-Access is a surprisingly excellent rapid development tool for quickly prototyping user interfaces, simple reports, table designs, and more.  I'd even strongly argue that business analysts should run a pilot to prototype screen, report, and in some cases even table designs in MS-Access.  Once the business logic is refined and edge cases surfaced, onlyh then hand it over as the defacto requirements for a software engineering team to completely re-write using professional development languages with architecture and scalability in mind.

Note also that the significant downsides of Access are avoided: 
(a) don't use it for data storage except for tiny temp tables...use the big DBMS platforms like MSSQL, Oracle, MySQL, and Postgresql, and 
(b) be careful implenting security: never store passwords, run as ACCDE to prevent source code access/tampering.

The plan is to re-write those prototypes that get widely used into either c#, python, or both...time permitting, a year or two down the line.


## Text Files


### [End-of-Line Editor](https://github.com/DataResearchLabs/sql_scripts/blob/main/data_dictionary_scripts.md)
The End-of-Line Editor tool and tutorials enable you to easily view and/or change the end-of-line character(s) in a target text file.  Data analysts trying to figure out why a text file is erroring can quickly spot that either the entire file has Linux end-of-line characters (LF) where PC is expected (CRLF).   Data analysts can also find that elusive one row that is ending with linefeed (LF) where all other rows end with PC EOL (CRLF).  Software and User Acceptance Testers can use this tool to quickly generate different file formats (PC, Linus/Unix, and old Mac).<br>
<br>
<br>




