# Online Pizza Shopping / DineKart (Java JSP Web App)

A web-based pizza ordering system built with JSP, HTML, Bootstrap, and JDBC.  
Users can browse pizzas, add items to cart, place orders, and generate receipts.  
Admins can manage menu items, orders, and customer details.

---

## 🚀 Features

### 👤 User
- Browse pizza menu
- Add to cart
- Place order
- Generate receipt
- Login & registration

### 🛠 Admin
- Add/update pizza items
- View customer details
- View orders and bills

---

## 🧱 Tech Stack

**Frontend**
- HTML5 / JSP
- Bootstrap
- JavaScript

**Backend**
- Java (JSP + Servlets)
- JDBC

**Database**
- PostgreSQL (schema included in `/database/database.sql`)

**Server**
- Apache Tomcat

---

## 📁 Project Structure

```
online-pizza-shopping/
 ├─ bootstrap/         # CSS & JS dependencies (Bootstrap)
 ├─ database/          # Database schema (.sql)
 ├─ images/            # Static project images/icons
 ├─ imp-files/         # Supporting assets (optional)
 ├─ jsp-pages/         # JSP-based UI screens
 ├─ scripts/           # JavaScript files
 ├─ WEB-INF/
 │    └─ lib/          # JDBC driver JARs
 ├─ *.jsp / *.html     # Main UI files
 └─ README.md
```

---

## 🗄 Database Setup

1. Install PostgreSQL
2. Create database:

```sql
CREATE DATABASE online_pizza_shopping;
```

3. Import schema from:
```
/database/database.sql
```

This will create the required tables for users, products, orders, and billing.

> Note: Password fields in the SQL schema are stored as plain text for demonstration purposes.  
> For production use, hashing is recommended.

---

## 🖥 Running the Project

### Prerequisites
- Java 8 or higher
- Apache Tomcat 8.x or newer
- PostgreSQL
- pgAdmin or psql CLI
- PostgreSQL JDBC Driver (available in `WEB-INF/lib/`)

### Steps
1. Clone the repository
2. Import the project into your IDE (Eclipse / IntelliJ / NetBeans)
3. Configure Apache Tomcat as a server
4. Configure database connection in JDBC code if required
5. Deploy the project to Tomcat
6. Start the server and open in browser:

```
http://localhost:8080/online-pizza-shopping
```

---

## 🔒 Demo Credentials (If applicable)

Add your demo admin/user credentials here, for example:

```
Admin:
username: admin
password: admin123
```

Remove this section if not applicable.

---

## 📸 Screenshots (Optional)

Place screenshots in `/screenshots` or `/images` folder and reference like:

```
![Home Page](images/home-page.png)
```

---

## 📄 License

This project is intended for learning/demo use.  
If open-sourcing publicly, choose a license such as MIT.

---

## 🤝 Contributing

Pull requests are welcome.  
For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

Author: Swapnil Pawar  
Purpose: Academic / Learning project

