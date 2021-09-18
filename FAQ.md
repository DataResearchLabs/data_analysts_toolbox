# FAQ - Frequently Asked Questions

## Q1. Why are these prototypes built in Microsoft Access?
A: I know...groan...but MS-Access is a surprisingly excellent rapid development tool for quickly prototyping user interfaces, simple reports, table designs, and more.  

I'd even strongly argue that business analysts should run a pilot to prototype screen, report, and in some cases even table designs in MS-Access.  Once the business logic is refined and edge cases surfaced, onlyh then hand it over as the defacto requirements for a software engineering team to completely re-write using professional development languages with architecture and scalability in mind.

Note also that the significant downsides of Access are avoided: <br>
(a) don't use it for data storage except for tiny temp tables...use the big DBMS platforms like MSSQL, Oracle, MySQL, and Postgresql, and <br>
(b) be careful implenting security: never store passwords, run as ACCDE to prevent source code access/tampering.

The plan is to re-write those prototypes that get widely used into either c#, python, or both...time permitting, a year or two down the line.
