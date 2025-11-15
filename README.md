#  SQL Server Database – Poem Website Database

This project is a **SQL Server database** designed to manage **poems, poets, and user interactions**.  
The database structure is stored in the `SiirWebSite_Database.sql` file.  
You can run this script in **SQL Server Management Studio (SSMS)** to recreate the same database in your local environment.

The database was built for a **poem sharing platform**,  
where users can read poems, post comments, give likes, and save poems to their personal reading lists.  
It features a **relational structure** between poets, poems, and categories.

---

##  Database Tables

| Name | Description |
|-------------|-------------------------|
| **Kullanici**  (User) | Stores user information. |
| **Sair** (Poet) |  Contains poet details. |
| **Siir** (Poem) | Stores poem titles, contents, and dates. |
| **Kategori**  (Category) | Contains poem categories. |
| **Begeni**  (Like) | Records user likes on poems. |
| **Yorum** (Comment) | Stores comments made by users. |
| **OkumaListesi** (ReadingList) | Stores users’ personal reading lists. |

---

## Stored Procedure

###  `SairinSiirleri`
Lists all poems written by the poet whose name is provided as a parameter.

---

## How to Use

**1.** Open the `SiirWebSite_Database.sql` file.  
**2.** Create a new query window in SQL Server Management Studio.  
**3.** Paste the code and press **Execute (F5)**.  
**4.** The database will be created automatically.

---

## Additional Info
-  Environment: Microsoft SQL Server 2022  
-  File Name: `SiirWebSite_Database.sql`  
-  Database Type: Relational (RDBMS)   

---

## Description
This database was created to demonstrate **backend data management** in software projects.  
It can easily be integrated into future web or mobile applications.

---

## Developer

**Name:** Zişan Yüce  
**Role:** Full Stack Developer & Computer Engineering Student  

---

⭐ If you like this project, don’t forget to give it a star!  


