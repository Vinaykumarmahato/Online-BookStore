# 📚 Online BookStore
![Project Logo](https://github.com/ADVindiancoder/Online-BookStore/blob/main/Screensort/Screenshot%20(63).png)

## 🚀 A Java Developer  Project

## About
- 📘 A user-friendly Online Bookstore project where users can:

- Log in or register
- View available books
- Select books with quantities
- Buy books
- Get payment receipts
- 
## 👩‍💼 Administrators can also:

- Add new books
- Remove books
- Manage book quantities and prices
- Maintain selling history
- online bookstore

## 🎯 Purpose
- 🛍️ For Selling books online.
- 📊 Maintaining books selling history.
- 📚 Adding and managing books.
- 🌟 User Friendly.
- 🚀 For Implementation of Http Servlets in Java.
- 📌 This is a Mini-project developed using Java, Jdbc, And Servlets.
## 👨‍💼 Admin Has Following Access for this online store

- ➕ Add New Books.
- 👁️ View Books Available.
- 🗑️ Remove Books.
- 🔺 Increase Books Amount.
## 👥 Users Have Following Access for this online store
- 🆕 Create New Account or Register.
- 🔑 Login.
- 📖 View Available Books.
- 🛒 Select Books to Buy.
- 📊 Select Books Quantity.
- 💳 Buy Books.
- 🧾 Get Payment Receipt.
## 🛠️ Technologies used:
### Front-End Development:

- 🌐 HTML
- 🎨 CSS
- 🚀 JavaScript
- 🅱️ Bootstrap
### Back-End Development:

- ☕ Java [JDK 8+]
- 🛢️ JDBC
- 🕸️ Servlet
### Database:

- 📊 MySQL

## 🛠️ Software And Tools Required:
- 🌐 Git Setup Guide
- ☕ Java JDK 8+ Setup Guide
- 💼 Eclipse EE (Enterprise Edition) Setup Guide
- 🧰 Apache Maven Setup Guide
- 🌐 Tomcat v8.0+ Setup Guide
- 🗄️ MySQL Server Setup Guide
- 🧑‍💻 MySQL Workbench (optional) Setup Guide
- 🗃️ Dummy Database Initialization:
 
- 📌 STEP 1: Open MySQL Command Prompt or MySQL Workbench.
- 📌 STEP 2: Login to the administrator user as : mysql -u <username> -p (Enter Password if asked).
- 📌 STEP 3: Copy-paste the following MySql Commands:
- 📂 create database if not exists onlinebookstore;

- 📂 use online BookStore;

- 📂 create table if not exists books(barcode varchar(100) primary key, name varchar(100), author varchar(100), price int, quantity int);

- 📂 create table if not exists users(username varchar(100) primary key,password varchar(100), firstname varchar(100), lastname varchar(100),address text, phone varchar(100),mailid varchar(100),usertype int);

- 📂 insert into books values('9780134190563','The Go Programming Language','Alan A. A. Donovan and Brian W. Kernighan',400,8);

- 📂 insert into books values('9780133053036','C++ Primer','Stanley Lippman and Josée Lajoie and Barbara Moo',976,13);

- 📂 insert into books values('9781718500457','The Rust Programming Language','Steve Klabnik and Carol Nichols',560,12);

- 📂 insert into books values('9781491910740','Head First Java','Kathy Sierra and Bert Bates and Trisha Gee',754,23);

- 📂 insert into books values('9781492056300','Fluent Python','Luciano Ramalho',1014,5);

- 📂 insert into books values('9781720043997','The Road to Learn React','Robin Wieruch',239,18);
- 📂 insert into books values('9780132350884','Clean Code: A Handbook of Agile Software Craftsmanship','Robert C Martin',288,3);

- 📂 insert into books values('9780132181273','Domain-Driven Design','Eric Evans',560,28);

- 📂 insert into books values('9781951204006','A Programmers Guide to Computer Science','William Springer',188,4);

 - 📂 insert into books values('9780316204552','The Soul of a New Machine','Tracy Kidder',293,30);

- 📂 insert into books values('9780132778046','Effective Java','Joshua Bloch',368,21);

- 📂 insert into books values('9781484255995','Practical Rust Projects','Shing Lyu',257,15);

- 📂 insert into users values('demo','demo','Demo','User','Demo Home','42502216225','demo@gmail.com',2);

- 📂 insert into users values('Admin','Admin','Mr.','Admin','Haldia WB','9584552224521','admin@gmail.com',1);

- 📂 insert into users values('Vinay','Vinay','vinay','Kumar','Bihar','9931860964','vinaykumar860964@gmail.com',2);

## 📜 commit;
- 🚀 Importing and Running The Project Through Eclipse EE:
- 🌐 Step 0: Open Eclipse Enterprise Edition. [Install, if not already installed.]

- 🌐 Step 1: Click On File > Import > Git > Projects From Git > Clone Uri > Paste The Repository URL as: git@github.com:ADVindiancoder/Online-BookStore.git > Select master Branch > Next > Next > Finish.

- 🌐 Step 2. a: Go inside src/main/resources > application.properties and update the value of database details as per your usage, like db.driver, db.host, db.username, and db.password according to your installed MySQL/postgresql admin user credentials.

- 🌐 Step 2.b: Right Click on Project > Run as > Maven Build > In the goals field, enter "clean install" > apply > run.

- 🌐 Step 2.c: Right Click On Project > Build Path > Configure Build Path > Libraries > Remove and Update Any Libraries if Red Mark Exists > Finish.

- 🌐 Step 3: [Only If Tomcat Server is not configured in Eclipse]: Right Click On Project > Run As > Run On Server > Select Tomcat V8.0 > (Select Tomcat V8.0 Installation Location If Asked) Next > Add online BookStore > Finish.

- 🌐 Step 4: In The Server Tab > Double Click On Tomcat Server > Ports > Change The Port Number For Http/1.1 To 8083 > Close And Save.

- 🌐 Step 5: Right Click On Project > Run As > Run On Server > Select Tomcat v8.0 > Next > Add All> Done.


- 🌐 Step 6: Default Username And Password For Admin Is "Admin" And "Admin"

- 🌐 Step 7: The default Username And Password For User Is "vinay" And "kumar"
## 🌐 FAQ
- 📜 Question:1 Unable to Connect to Database?

- 📝 Answer: Please check you have installed MySQL correctly and have updated the correct db details in application.properties file. Also, you can try doing maven clean install and force update the project and restart.


## 🖼️ 📷 Take a look at these project screenshots:
![Project Logo](https://github.com/ADVindiancoder/Online-BookStore/blob/main/Screensort/Screenshot%20(61).png)

![Project Logo](https://github.com/ADVindiancoder/Online-BookStore/blob/main/Screensort/Screenshot%20(65).png
)
![Project Logo](https://github.com/ADVindiancoder/Online-BookStore/blob/main/Screensort/Screenshot%20(66).png)
![Project Logo](https://github.com/ADVindiancoder/Online-BookStore/blob/main/Screensort/Screenshot%20(68).png)
![Project Logo](https://github.com/ADVindiancoder/Online-BookStore/blob/main/Screensort/Screenshot%20(69).png
)
![Project Logo](https://github.com/ADVindiancoder/Online-BookStore/blob/main/Screensort/Screenshot%20(70).png)




### 🚀 Feel free to share your thoughts and suggestions for enhancing the project! We value your input and ideas! 🌟

### 👨‍💼 This project idea was inspired by my experiences and skills gained during my Java DSA System Design course, with leadership by PW Skills (Ineuran).
