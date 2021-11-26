MyBatis JPetStore
=================

[![Build Status](https://travis-ci.org/mybatis/jpetstore-6.svg?branch=master)](https://travis-ci.org/mybatis/jpetstore-6)
[![Coverage Status](https://coveralls.io/repos/github/mybatis/jpetstore-6/badge.svg?branch=master)](https://coveralls.io/github/mybatis/jpetstore-6?branch=master)
[![License](http://img.shields.io/:license-apache-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

![mybatis-jpetstore](http://mybatis.github.io/images/mybatis-logo.png)

JPetStore 6 is a full web application built on top of MyBatis 3, Spring 5 and Stripes.
 
- Clone this repository

  ```
  ## HSQL
  $ git clone https://github.com/nationminu/jpetstore-sample.git -b master
  
  ## JNDI Lookup
  $ export JAVA_OPTS="-DDB_JNDI=java:comp/env/jdbc/petstore"
  $ git clone https://github.com/nationminu/jpetstore-sample.git -b jndi
  
  ## DBCP2 Datasource
  $ export JAVA_OPTS="-DDB_CLASS=com.mysql.cj.jdbc.Driver -DDB_URL='jdbc:mysql://hostname:3306/petstore' -DDB_USERNAME=petstore -DDB_PASSWORD=petstore"
  $ git clone https://github.com/nationminu/jpetstore-sample.git -b dbcp2
  ``` 

- Build war file

  ```
  $ cd jpetstore-6
  $ ./mvnw clean package
  ```
 
