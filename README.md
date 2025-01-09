# **Ebook Management System**
## **Overview**
The **Ebook Management System** is a Java web application designed to manage eBooks efficiently.  
Users can register, browse, upload, and download eBooks, while administrators have advanced management capabilities.
### **Purpose**
The system aims to simplify eBook storage and access for book enthusiasts and administrators.
## **Features**

- **User Features:**  
  - Register and log in securely.  
  - Search for books by title, author, or category.
   
- **Admin Features:**  
  - Manage book records (add, edit, delete).  
  - View and manage user accounts.  
---
## **Technologies Used**

### **Frontend**
- HTML  
- CSS  
- JavaScript  
- Bootstrap  

### **Backend**
- Java Servlets  
- Java Server Pages (JSP)  

### **Database**
- MySQL  

### **Server**
- Apache Tomcat  

### **Tools**
- Eclipse IDE  
- Maven  

---
## **Installation**

Follow these steps to set up the project locally:

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/username/ebook-management-system.git
2. Open the project in Eclipse:
Select File > Import > Existing Maven Projects.
Choose the project directory.

4. Set up the database:
Import the provided ebook_system.sql file into MySQL.
Update database credentials in the Database Connection class:
```bash
 String url = "jdbc:mysql://localhost:3306/ebook_system";
 String username = "root";
 String password = "your_password";


