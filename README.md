## SQL Server Interview Questions

### 1. Can we make float as primary key column, If yes How will increment work?<br/>
- Yes we can create Float column as a primary key column. That float column don't have scale value means it should be 0.<br/>
For ex :- DECIMAL(16,0) IDENTITY(1,1)<br/>
And other option is set manually value then it accept everything<hr/>

### 2. What is the function in sql server and how many types they are?<br/>
- https://docs.microsoft.com/en-us/sql/relational-databases/user-defined-functions/user-defined-functions?view=sql-server-ver15<hr/>

### 3. What is procedure in sql server?<br/>
- https://docs.microsoft.com/en-us/sql/t-sql/statements/create-procedure-transact-sql?view=sql-server-ver15<hr/>

### 4. What is the trigger in sql server and it's Type?<br/>
- https://docs.microsoft.com/en-us/sql/t-sql/statements/create-trigger-transact-sql?view=sql-server-ver15<hr/>

### 5. What is ACID Properties in DBMS?<br/>
- https://en.wikipedia.org/wiki/ACID
- https://www.geeksforgeeks.org/acid-properties-in-dbms/<hr/>

### 6. What difference between storeprocedure and views?<br/>
- Views :- 
- - A view is a virtual table whose contents are defined by a query.
- - In a view we are able to write just select query not any DML operation.
- - If a view is created with table then we are not able to drop that table.
- https://docs.microsoft.com/en-us/sql/relational-databases/views/views?view=sql-server-ver16

- Storeprocedure :-
- - It is nothing JUST a group of SQL statements and which takes some input and perform task and return some output.
- - In stored procedure we are able to perform CRUD operation.
- - We are able to call another procedure and function inside procedure.
- https://www.geeksforgeeks.org/what-is-stored-procedures-in-sql/

