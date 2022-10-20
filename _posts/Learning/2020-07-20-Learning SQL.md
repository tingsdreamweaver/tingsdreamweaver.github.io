---
layout: post
title: Learning SQL 
category: Learning
tags: sql
keywords: sql
---

## 1 Basic learning process
1. Learn basic knowledge of database
2. Install a database (Postgresql or MySQL)
3. Find a good SQL website or book for reference
4. Build a basic mindmap of SQL grammar  (via an online course or a book)
5. Exercise and apply the knowledge at work (THE MOST IMPORTANT PART. We need to type the code by ourselves instead of using copy paste.)

## 2 Tips
- To end your statements with a semicolon(;) - It's not mandatory but it's a good habit. 
- It is very forgiving in terms of upper/lower case, extra spaces, and line breaks.
- Don't copy paste code. It's better to type it to get the "mussle memory.

## 3 SQL Reference

### 1) Database Documentation
- [PostgreSQL 14.5 Documentation](https://www.postgresql.org/docs/current/index.html)
- [SQL reference for Amazon S3 Select and S3 Glacier Select](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-glacier-select-sql-reference.html)

### 2) SQL Online Learning Resources
- [SQLBolt](https://sqlbolt.com/) Friendly interface. It explains the functions of SQL statements in detail, and provides an interactive online programming environment to experience the usage of SQL. No registration required.
- [SQLZOO](https://zh.sqlzoo.net/wiki/SQL_Tutorial) For exercises.
- [W3school](http://www.w3school.com.cn/sql/) Quickly check basic SQL commands and understand the meaning and usage of SQL commands. Finally do a SQL test to see if the basic SQL concepts are established.
- [W3school SQL exercise](http://www.w3resource.com/sql-exercises/) The questions are rich but basic. It provides an interactive programming window, but the interface is not friendly enough. It is suitable for a recap after having mastered SQL in general.
- [50 questions for sql](https://www.jianshu.com/p/476b52ee4f1b)
- [the answers for the 50 questions](https://blog.csdn.net/woooooood/article/details/85163780)

### 2) SQL Books
-  'Head First SQL: Your Brain on SQL -- A Learner's Guide' - Lynn
-  'MySQL Crash Course'

## 4 Process of write a query
1. Decide on the output you want (list of columns)
2. Identify the tables
3. Identify the necessary filters
	1. time/place/product
	2. partition columns
	3. unwanted data
4. Decide if subqueries will be necessary and plan the structure
5. write the SQL
6. double check your partition filters and join conditions are sufficient
7. Test and check for errors
8. run query

## 5 Mindmap
![](/public/img/database/SQL.png)

