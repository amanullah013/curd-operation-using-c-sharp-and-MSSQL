CRUD-operations-using-C-Sharp-and-MSSQL-Server-database
Desktop CRUD App Written In C#(.NET Framework)

Project Overview
-This project demonstrates how to implement CRUD (Create, Read, Update, Delete) operations using C# and SQL Server within a Windows orms Application. It provides a user-friendly interface for managing student records.






### Bulit With
- C#(.Net Framework)
- Microsoft Sql
- Microsoft Visual Studio

- ## Features

- Insert Data
- Delete Data
- Update Data
- Search Data

- ## SQL Query
#### Design Table
```bash
CREATE TABLE [dbo].[CURDForm] (
    [Id]     INT          NOT NULL,
    [Name]   VARCHAR (50) NULL,
    [salary] VARCHAR (50) NULL,
    [city]   VARCHAR (50) NULL,
    PRIMARY KEY CLUSTERED ([Id] ASC)
);
```
#### Insert Data
```bash
insert into CURDForm values (@id,@name,@salary,@city)
```
#### Delete Data
```bash
delete CURDForm where id=@id
```
#### Update Data
```bash
update CURDForm set name=@name,salary=@salary,city=@city where id=@id
```
#### Search Data
```bash
select * from CURDForm where id = @id
```
## Tech Stack

**Programming Language:** C# <br><br>
**Database:** SQL Server<br><br>
**Framework:** Windows Forms<br><br>
**UI Components:** <br>
    -Text Box for entering data.<br>
    - Button for response.<br>
    - Data Grid View for displaying and managing data


## 🛠 Skills
C#, .NET, SQL
