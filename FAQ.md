# FAQ - Frequently Asked Questions

<a id="q01" class="anchor" href="#q01" aria-hidden="true"> </a>
### Q01. Why are these prototypes built in Microsoft Access?
A1: I know...groan...but MS-Access is a surprisingly excellent rapid development tool for quickly prototyping user interfaces, simple reports, table designs, and more.<br><br>

A2: Also, I am "nostalgically biased"...having coded in everything from c# to Python to Java to Visual Basic with some Ada and Fortran in there too...but my fondest memories are way back in the beginning doing VBA in Access in the mid-1990's.<br><br>  

A3: I'd even argue the case can be made that for new, small, internal projects that business analysts should run a pilot to prototype screen, report, and in some cases even table designs in MS-Access.  Once the business logic is refined and edge cases surfaced, only then hand it over as the defacto requirements for a software engineering team to completely re-write using professional development languages with architecture and scalability in mind.

Note also that the significant downsides of Access are avoided: <br>
(a) don't use it for data storage except for tiny temp tables...use the big DBMS platforms like MSSQL, Oracle, MySQL, and Postgresql, and <br>
(b) be careful implenting security: never store passwords, run as ACCDE to prevent source code access/tampering.

The plan is to re-write those prototypes that get widely used into either c#, python, or both...time permitting, a year or two down the line.
