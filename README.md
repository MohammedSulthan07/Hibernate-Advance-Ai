# Hibernate-Advance

A collection of advanced Java Hibernate projects demonstrating powerful ORM features beyond basic CRUD operations. This repository focuses on advanced Hibernate concepts such as UUID-based primary keys, entity lifecycle management, advanced mappings, and best practices for building scalable Java applications using Hibernate ORM and MySQL.

---

## 📂 Repository Structure

```
Hibernate-Advance/
│
├── Demo002-UUID/
└── Demo02-Hibernate/
```

---

## 📚 Projects Included

### 1. Demo002-UUID

A Hibernate project demonstrating the use of **UUID (Universally Unique Identifier)** as primary keys instead of traditional auto-increment IDs.

**Features:**

- UUID Primary Key Generation
- Entity Mapping
- Hibernate Annotations
- Session Management
- Transaction Management
- CRUD Operations
- MySQL Integration

**Concepts Covered:**

- UUID Generation
- `@Id`
- `@GeneratedValue`
- Hibernate UUID Generator
- Entity Persistence

---

### 2. Demo02-Hibernate

An advanced Hibernate practice project covering various ORM concepts and database operations.

**Features:**

- CRUD Operations
- Hibernate Configuration
- SessionFactory
- Session Management
- Transaction Handling
- Advanced Entity Mapping
- Annotation-Based Configuration
- Exception Handling
- MySQL Integration

**Concepts Covered:**

- Entity Lifecycle
- Persistent Objects
- Detached Objects
- Transient Objects
- Dirty Checking
- Flush Operations
- Transaction Management
- Fetch Strategies
- Cascade Operations

---

# 🛠 Technologies Used

- Java
- Hibernate ORM
- Jakarta Persistence API (JPA)
- MySQL
- Maven
- Eclipse IDE / IntelliJ IDEA
- Git
- GitHub

---

# 📋 Requirements

Before running the projects, install the following:

- JDK 17 or above
- MySQL Server
- MySQL Workbench (Optional)
- Maven
- Eclipse IDE or IntelliJ IDEA

---

# ⚙ Database Configuration

Update your Hibernate configuration file (`hibernate.cfg.xml` or `hibernate.properties`) with your database credentials.

Example:

```xml
<property name="hibernate.connection.url">
    jdbc:mysql://localhost:3306/your_database
</property>

<property name="hibernate.connection.username">
    root
</property>

<property name="hibernate.connection.password">
    your_password
</property>
```

Ensure that:

- MySQL Server is running.
- The required database has been created.
- Hibernate is configured correctly.
- Required tables are created automatically or manually.

---

# ▶ Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/Hibernate-Advance.git
```

### 2. Import the project

Open the project in Eclipse or IntelliJ IDEA.

### 3. Configure the database

Update your database credentials inside the Hibernate configuration file.

### 4. Build the project

If using Maven:

```bash
mvn clean install
```

### 5. Run the Main Class

Execute the main application class to start the project.

---

# 📖 Advanced Hibernate Concepts Covered

This repository demonstrates many advanced Hibernate features, including:

- UUID Primary Key Generation
- Entity Lifecycle States
- SessionFactory
- Session Management
- Transactions
- Dirty Checking
- Flush and Clear Operations
- First-Level Cache
- Cascade Types
- Fetch Strategies
- Annotation-Based Mapping
- Primary Key Strategies
- CRUD Operations
- Exception Handling
- Hibernate Configuration
- Maven Project Structure

---

# 🎯 Learning Objectives

This repository is intended for developers and students who want to learn:

- Advanced Hibernate ORM
- UUID-Based Entity Management
- Hibernate Session Lifecycle
- Transaction Management
- Object Relational Mapping (ORM)
- Java Persistence API (JPA)
- Best Practices in Hibernate
- Enterprise Java Development

---

# 🚀 Future Improvements

Future projects planned for this repository include:

- HQL (Hibernate Query Language)
- JPQL
- Criteria API
- Named Queries
- Native SQL Queries
- Pagination
- Batch Processing
- Composite Primary Keys
- Embeddable Classes
- Inheritance Mapping
- Second-Level Cache (Ehcache)
- Optimistic & Pessimistic Locking
- Spring Data JPA
- Spring Boot Integration
- REST APIs with Hibernate

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Create a Pull Request.

---

# 👨‍💻 Author

**Mohammed Sulthan**

GitHub: https://github.com/MohammedSulthan07

---

# ⭐ Support

If you found this repository helpful, please consider giving it a **Star ⭐** on GitHub.

Happy Coding! 🚀
