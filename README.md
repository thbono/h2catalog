# h2catalog
For tests using H2 in-memory database and catalog mapped JPA entities, used in systems that runs over catalog databases (like Microsoft SQL Server)

The code was adapted to ignore the catalog. In any SQL, the qualifier catalog.schema.table will be interpreted as schema.table

Fork of https://code.google.com/p/h2database at version 1.4.187

Subversion: http://h2database.googlecode.com/svn/trunk/ at revision r6122

JDK: 1.6.45