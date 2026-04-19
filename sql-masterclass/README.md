# SQL 마스터클래스

### #1 INTRODUCTION

#### #1.3 Why You Should Learn SQL (26.04.18)

- SQL을 배워야하는 이유
  - 데이터는 어디에나 있음
  - 데이터는 데이터베이스 내에 존재
  - 대부분의 데이터베이스들이 SQL을 사용
  - SQL은 데이터베이스와 통신하는데 사용되는 언어
- 린디 효과 : 기술이나 아이디어의 미래 수명은 해당 기술이 얼마나 오래 살아남았는지에 따라 예측
  - SQL은 50년간 살아남았으니 향후 50년 동안 SQL이 사용될 가능성은 매우 높음
- ORM : 프로그래밍 언어 구조로 이루어진 객체를 SQL 코드로 번역 해주는 도구
  - 개발자들은 SQL 코드를 작성할 필요없고 사용하고 있는 프로그래밍 언어로 만든 객체를 SQL 쿼리로 변환

#### #1.4 What is SQL (26.04.20)

- SQL은 1970년대 만들어졌음
  - SQL의 창시자는 SQUARE라는 데이터베이스를 만들었음
  - SQUARE 보다 더 나은 SEQUEL를 만들었음
  - SEQUEL(Structured English Query Language)은 당시 단어가 저작권에 걸림
  - 그래서 만들어진게 SQL(Structured Query Language)
  - SQL은 RDBMS라고 불리는 것 안에 있는 데이터를 관리하기 위해서 사용
- RDBMS (Relational Database Management System)
  - 관계형 데이터베이스와 대화할 수 있게 해주는 프로그램
  - SQLite, MySQL, PostgreSQL, MariaDB, Microsoft SQL Server, Oracle SQL
- 관계형 데이터베이스는 데이터들을 테이블 안에 저장하는 데이터베이스
  - 엑셀 시트처럼 데이터를 정리하는 데이터베이스라고 생각하면 됨
  - 행과 열이 있는 테이블에 데이터를 저장하는 데이터베이스
- SQL은 선언형 언어
  - 선언형이라는 것은 SQL로 무언가를 하는 방법을 설명할 필요가 없다는 것
  - 원하는 것만 말하면 됨
- 이식성이란 sqlite에서 작성한 코드가 postgreSQL, MariaDB, MySQL에서도 잘 작동하는가?
  - SQL에는 표준이 존재하지만 해당 표준을 100% 구현하는 데이터베이스는 없음
  - 같은 언어를 사용한다고 해서 기능이 같거나 서로 상호작용 가능하다는 것은 아님
- 개념은 이식성이 있음
  - Data Types, Table, Rows, Columns 등과 같은 개념은 이식 가능
  - SELECT, Group By, Aggregate functions 등은 모두 이식 가능
- SQL은 그 자체로 하나의 언어가 아님
  - Data Definition Language (DDL) : 데이터베이스에 들어갈 데이터를 정의할 때 사용하는 언어
    - 기본적으로 데이터베이스에 우리가 저장할 데이터의 타입을 설명하는데 사용
  - Data Manipulation Language (DML) : 데이터를 조작할 때 사용하는 언어
    - 데이터베이스에 데이터를 넣거나, 업데이트하거나, 삭제할 때 사용
    - 데이터베이스에서 데이터를 select하고 query하는데도 사용
  - Transaction Control Language (TCL)
  - Data Control Language (DCL) : 누가 읽고, 수정할 수 있는지를 설정

#### #1.5 Course Roadmap

#### #1.6 How To Get Help

#### #1.7 Required Software

### #2 SQLite

#### #2.0 Introduction

#### #2.1 Installation

#### #2.2 Database Creation

#### #2.3 Beekeper Studio

#### #2.4 TablePlus

### #3 Data Definition Language

#### #3.0 Introduction

#### #3.1 Tables

#### #3.2 CREATE TABLE

#### #3.3 INSERT INTO VALUES

#### #3.4 INSERT INTO VALUES part Two

#### #3.5 Data Types

#### #3.6 Constraints

#### #3.7 CHECK Constraint

#### #3.8 Recap

#### #3.9 Primary Keys

### #4 Data Manipulation Language

#### #4.0 Introduction

#### #4.1 Update Commands

#### #4.2 SELECT Command

#### #4.3 FROM Clause

#### #4.4 SELECT Expressions

#### #4.5 Movies Database

#### #4.6 WHERE Clause

#### #4.7 WHERE Predicates

#### #4.8 SELECT CASE

#### #4.9 ORDER BY Clause

#### #4.10 LIMIT and OFFSET Clauses

#### #4.11 GROUP BY Clause

#### #4.12 GROUP BY Gotchas

#### #4.13 HAVING Clause

#### #4.14 Super Practice Part One

#### #4.15 Super Practice Part Two

#### #4.16 Super Practice Part Three

#### #4.17 Views

### #5 Subqueries and CTEs

#### #5.0 Introduction

#### #5.1 Independent Subqueries

#### #5.2 CTEs

#### #5.3 Correlated Subqueries

#### #5.4 Correlated CTEs

#### #5.5 Subquery Practice

#### #5.6 Final Practice

### #6 Indexes

#### #6.0 Introduction

#### #6.1 Table Scans

#### #6.2 CREATE INDEX

#### #6.3 Disclaimer

#### #6.4 B+ Trees

#### #6.5 Leaf Nodes

#### #6.6 Recap

#### #6.7 Indexes and Keys

#### #6.8 Multi Column Indexes

#### #6.9 Covering Indexes

#### #6.10 When To Use Indexes

### #7 MySQL

#### #7.0 Introduction

#### #7.1 Installation

#### #7.2 MySQLWorkbench

#### #7.3 Connectiong

#### #7.4 MySQL Data Types Part One

#### #7.5 MySQL Data Types Part Two

#### #7.6 INSERT INTO VALUES

#### #7.7 ALTER TABLE

#### #7.8 ALTER TABLE part Two

#### #7.9 Generated Columns

#### #7.10 Data Import

### #8 Foreign Keys

#### #8.0 Introduction

#### #8.1 Data Normalization

#### #8.2 Entities

#### #8.3 Foreign Keys

#### #8.4 ON DELETE

#### #8.5 One-To-Many and One-To-One

#### #8.6 Many-To-Many

### #9 Joins

#### #9.0 Introduction

#### #9.1 CROSS JOIN

#### #9.2 INNER JOIN

#### #9.3 OUTER JOIN

#### #9.4 Joins Practice

#### #9.5 Joins Practice part Two

#### #9.6 Joins Practice part Three

### #10 Normalization

#### #10.0 Introduction

#### #10.1 Normalizing Status

#### #10.2 Normalizing Directors

#### #10.3 Normalizing Original Language

#### #10.4 Normalizing Countries

#### #10.5 Unions

#### #10.6 Conclusions

### #11 Events & Triggers

#### #11.0 Introduction

#### #11.1 Events

#### #11.2 Recap

#### #11.3 Triggers

#### #11.4 Overpowered Trigger

### #12 Fulltext Indexes

#### #12.0 Introduction

#### #12.1 Natural Language Search

#### #12.2 Boolean Mode Search

#### #12.3 Query Expansion

### #13 PostgreSQL

#### #13.0 Introduction

#### #13.1 Installation

#### #13.2 pgAdmin

#### #13.3 PostgreSQL Data Types

#### #13.4 PostgreSQL Data Types part Two

#### #13.5 Type Casting

#### #13.6 Data Import

#### #13.7 UNNEST

#### #13.8 FULL OUTER JOIN

### #14 Functions and Procedures

#### #14.0 Introduction

#### #14.1 Functions

#### #14.2 Return Types

#### #14.3 Trigger Functions

#### #14.4 Procedures

#### #14.5 Python Extension

### #15 Transactions

#### #15.0 Introduction

#### #15.1 Transactions Are Awesome

#### #15.2 ACID

#### #15.3 Savepoints

#### #15.4 Read Uncommited

#### #15.5 Repeatable Read

#### #15.6 Phantom Read

#### #15.7 Locks

#### #15.8 Serialization Anomaly

#### #15.9 Shared Locks

### #16 Data Control Language

#### #16.0 Introduction

#### #16.1 Users

#### #16.2 Roles

### #17 PostgreSQL JSON Columns

#### #17.0 Introduction

#### #17.1 JSON and JSONB

#### #17.2 Querying JSON

#### #17.3 Processing JSON

### #18 PostgreSQL Extensions

#### #18.0 Introduction

#### #18.1 HSTORE

#### #18.2 PGCrypto

#### #18.3 UUID

### #19 MongoDB

#### #19.0 Introduction

#### #19.1 Installation

#### #19.2 Creating Documents

#### #19.3 Reading Documents

#### #19.4 Updating Documents

#### #19.5 Aggregating Documents

### #20 Redis

#### #20.0 Introduction

#### #20.1 Installation

#### #20.2 Strings

#### #20.3 Lists

#### #20.4 Sets

#### #20.5 Hashes

#### #20.6 Sorted Sets

#### #20.7 Conclusions

### #21 JavaScript and Python Drivers

#### #21.0 Introduction

#### #21.1 Inserting Data

#### #21.2 SQL Injection

#### #21.3 Placeholders

#### #21.4 Querying Data

#### #21.5 MySQL and PostgreSQL Drivers

#### #21.6 Redis Caching

#### #21.7 PyMongo

#### #21.8 Drizzle Introspect

#### #21.9 Drizzle Migrate

#### #21.10 Redis

#### #21.11 Mongoose

#### #21.12 Conclusions
