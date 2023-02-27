# Hive-Hands-On

Apache Hive is a data warehousing tool built on top of Hadoop. It allows you to query and analyze large datasets stored in Hadoop Distributed File System (HDFS) or other compatible file systems using SQL-like queries. Hive provides a familiar SQL-like interface to Hadoop, which makes it easier for business analysts and SQL developers to work with big data.


Data types in hive

In Hive, the following are the data types that are supported:

    Numeric types:
        TINYINT: 1-byte signed integer (-128 to 127)
        SMALLINT: 2-byte signed integer (-32,768 to 32,767)
        INT: 4-byte signed integer (-2,147,483,648 to 2,147,483,647)
        BIGINT: 8-byte signed integer (-9,223,372,036,854,775,808 to 9,223,372,036,854,775,807)
        FLOAT: Single precision floating-point number
        DOUBLE: Double precision floating-point number
        DECIMAL: Arbitrary-precision decimal number

    Date/time types:
        TIMESTAMP: A timestamp consisting of year, month, day, hour, minute, and second
        DATE: A date consisting of year, month, and day

    String types:
        STRING: Variable-length character string
        CHAR: Fixed-length character string
        VARCHAR: Variable-length character string with a maximum length

    Complex types:
        ARRAY: Collection of elements with the same data type
        MAP: Collection of key-value pairs
        STRUCT: A complex data type that consists of multiple fields

    Other types:
        BOOLEAN: Logical Boolean (true or false)
        BINARY: Variable-length binary data
