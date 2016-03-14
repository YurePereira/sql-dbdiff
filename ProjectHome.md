# sql-dbdiff #

## Release v0.4 ##
Fourth release (**Fixed big Constraints issue!**), please head on over to the downloads page to grab it. Check out <a href='http://spikedsoftware.co.uk/blog/'>Spiked Software's Blog</a> to see what's new in the release.

### pre-amble ###
Originally developed here http://opendbiff.codeplex.com/. I'm branching it and making my own version, with some changes. Also, this version has everything in the subversion repository required to run it. No need to install the 3rd party requirements.

sql-dbdiff is an open source database schema comparison tool for MS SQL Server 2005+ (any version).
It reports differences between two database schemas and provides a synchronization script to upgrade a database from one to the other.

read: I do not support SQL 2000

### Description ###
sql-dbdiff can synchronize<br />
Tables (including Table Options like vardecimal, text in row, etc.)<br />
Columns (including Computed Columns, XML options, Identities, etc.)<br />
Constraints<br />
Indexes (and XML Indexes)<br />
XML Schemas<br />
Table Types<br />
User Data Types (UDT)<br />
CLR Objects (Assemblies, CLR-UDT, CLR-Store Procedure, CLR-Triggers)<br />
Triggers (including DDL Triggers)<br />
Synonyms<br />
Schemas<br />
File groups<br />
Views<br />
Functions<br />
Store Procedures<br />
Partition Functions/Schemes<br />
Users<br />
Roles

### To Come... ###
Cleaner UI<br />
Execute Change Script<br />
