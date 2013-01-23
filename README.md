ms-sql-gold-grammar
===================

A T-SQL grammar for Gold Parser

This grammar parses a subset of SQL commands. It parses many of my productive SQL scripts, views and procedures as long as they do not contain 
* "weird" characters in strings
* (NOLOCK) 
* additional white space or comment in "FOR READ ONLY"  in cursor definitions.

