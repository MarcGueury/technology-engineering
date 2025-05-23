# Database In-Memory

Database In-Memory features a highly optimized In-Memory Column Store (IM column store) maintained alongside the existing buffer cache. The primary purpose of the IM column store is to accelerate columnoriented data accesses made by analytic operations. It is similar in spirit to having a conventional index (for analytics) on every column in a table. However, it is much more lightweight than a conventional index, requiring no logging, or any writes to the database. Just as the performance benefit to an application from conventional indexes depends on the amount of time the application spends accessing data in the tables that are indexed, the benefit from the IM column store also depends on the amount of time the application spends on data access for analytic operations. It is therefore important to understand the basic characteristics of your application to determine the potential benefits from Database In-Memory.

Review Date: 20.11.2024 

## Useful Links

### Documentation

- [Database In-Memory](https://www.oracle.com/database/in-memory/)
- [Database In-Memory Guide](https://docs.oracle.com/en/database/oracle/oracle-database/23/inmem/index.html#Oracle%C2%AE-Database)
- [Oracle Database In-Memory Option (DBIM) Basics and Interaction with Data Warehousing Features (Doc ID 1903683.1)](https://support.oracle.com/epmos/faces/DocumentDisplay?_afrLoop=286800017302956&id=1903683.1&_afrWindowMode=0&_adf.ctrl-state=k8hteq5ab_4)
- [Oracle Database In-Memory Data Sheet](https://www.oracle.com/a/otn/docs/database/database-in-memory-datasheet.pdf)
  
### Team Publications

- [When and How to use Oracle Database In-Memory Advisor](https://blogs.oracle.com/coretec/post/how-to-use-oracle-database-in-memory-advisor)
- [Running Oracle Database In-Memory Advisor Offline](https://blogs.oracle.com/coretec/post/running-oracle-database-in-memory-advisor-of-one-database-on-another)
- [Oracle Database In-Memory - Getting Started](https://blogs.oracle.com/coretec/post/oracle-database-in-memory---getting-started-with-oracle-database-21-xe-and-sql-developer)

### Blogs and technical briefs

- [New Database In-Memory Features in Oracle Database 23ai](https://blogs.oracle.com/in-memory/post/dbim-new-features-23ai)
- [DBIM Resources](https://blogs.oracle.com/in-memory/post/dbim-resources)
- [Oracle Database In-Memory postings](https://blogs.oracle.com/in-memory/)
- [New In-Memory Eligibility Test](https://blogs.oracle.com/in-memory/post/inmemory-eligibility-test#:~:text=The%20purpose%20of%20the%20eligibility%20test%20is%20to,to%20get%20more%20information%20about%20your%20analytic%20workload.)
- [When to Use Oracle Database In-Memory](https://www.oracle.com/docs/tech/when-to-use-oracle-database-in-memory.pdf)
- [Oracle Database In-Memory Implementation Guidelines](https://www.oracle.com/technetwork/database/in-memory/learnmore/twp-oracle-dbim-implementation-3863029.pdf)

### LiveLabs
- [Boost Analytics Performance with Oracle Database In-Memory](https://apexapps.oracle.com/pls/apex/r/dbpm/livelabs/view-workshop?wid=566&clear=RR,180&session=4309406781047)
- [Database In-Memory Advanced Features](https://apexapps.oracle.com/pls/apex/r/dbpm/livelabs/view-workshop?wid=3710&clear=RR,180&session=4309406781047)

# License

Copyright (c) 2025 Oracle and/or its affiliates.

Licensed under the Universal Permissive License (UPL), Version 1.0.

See [LICENSE](https://github.com/oracle-devrel/technology-engineering/blob/main/LICENSE) for more details.
