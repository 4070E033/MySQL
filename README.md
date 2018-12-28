# MySQL

DROP DATABASE IF EXISTS cmdev;
建立資料庫

CREATE DATABASE cmdev CHARACTER SET big5;
big5編碼

USE cmdev;
使用資料庫

DROP TABLE IF EXISTS emp;
刪除資料庫

CREATE TABLE emp (

empno INT NOT NULL, 
  數字數據類型，不能包含空值
  
   ename VARCHAR(16) NOT NULL,
  數字數據類型，最大字元為16，不能包含空值
  
  job VARCHAR(16),
  
  manager INT,
  hiredate DATE,
  salary float(7, 2),
  comm float(7,2),
  deptno INT,
  PRIMARY KEY (empno)
);
  
     
     
