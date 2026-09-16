# 🚗 Car Rental System

A **Java-based Car Rental System** that allows users to rent and return cars through an interactive console application. The project demonstrates core **Java programming concepts, Object-Oriented Programming (OOP), collections, and basic system management**.

## 📌 Overview

The **Car Rental System** is a console-based application designed to simulate the basic operations of a car rental service.

Users can:

* 🚗 View available cars
* 🔑 Rent a car
* 🔄 Return a rented car
* 👤 Add and manage customers
* 🚘 Manage car information
* 💰 Calculate rental costs
* 📋 Maintain rental records

This project was developed to strengthen practical understanding of **Java fundamentals and OOP concepts**.

---

## ✨ Features

### 🚗 Car Management

* Add and manage cars
* Store car details such as:

  * Car ID
  * Brand
  * Model
  * Rental price
  * Availability status
* Display available cars

### 👥 Customer Management

* Add new customers
* Store customer information
* Identify customers using customer IDs

### 🔑 Rent a Car

* Select a car from the available cars
* Enter customer details
* Specify the rental duration
* Calculate the total rental cost
* Update car availability

### 🔄 Return a Car

* Return a previously rented car
* Update the car's availability status
* Calculate/display rental information

### 📋 Rental History

* Keep track of rental transactions
* Store customer and car details
* Maintain rental duration and cost information

---

## 🛠️ Technologies Used

* **Java**
* **Object-Oriented Programming (OOP)**
* **Java Collections**
* **Scanner for User Input**
* **Git & GitHub**

### Java Concepts Used

* Classes & Objects
* Encapsulation
* Constructors
* Methods
* Inheritance
* Polymorphism
* ArrayList
* Conditional Statements
* Loops
* Exception Handling
* User Input Handling

---

## 📂 Project Structure

```text
Car-Rental-System/
│
├── src/
│   ├── Car.java
│   ├── Customer.java
│   ├── Rental.java
│   └── CarRentalSystem.java
│
├── README.md
└── .gitignore
```

> The exact file names may vary depending on the implementation.

---

## ⚙️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/car-rental-system.git
```

### 2. Navigate to the Project

```bash
cd car-rental-system
```

### 3. Compile the Java Files

```bash
javac *.java
```

### 4. Run the Application

```bash
java CarRentalSystem
```

---

## 🖥️ How It Works

When the application starts, users are presented with a menu similar to:

```text
========== Car Rental System ==========

1. View Available Cars
2. Rent a Car
3. Return a Car
4. Add Customer
5. View Rental History
6. Exit

Enter your choice:
```

### Example

```text
Enter your choice: 2

Enter Customer ID: C101
Enter Car ID: CAR01
Enter Rental Duration: 3 days

Car rented successfully!

Total Rental Cost: ₹4500
```

After renting a car, its availability is automatically updated.

---

## 💡 OOP Design

The project follows Object-Oriented Programming principles.

### `Car`

Represents a vehicle available for rental.

```text
Car
├── carId
├── brand
├── model
├── pricePerDay
└── available
```

### `Customer`

Represents a customer using the rental service.

```text
Customer
├── customerId
└── name
```

### `Rental`

Represents a rental transaction.

```text
Rental
├── customer
├── car
├── rentalDays
└── totalCost
```

### `CarRentalSystem`

Acts as the main controller of the application and handles:

* Car management
* Customer management
* Rental operations
* Return operations
* Rental history

---

## 🎯 Learning Objectives

This project helped in understanding and implementing:

* Java fundamentals
* Object-Oriented Programming
* Classes and objects
* Encapsulation
* Collections in Java
* User input handling
* Basic application architecture
* Real-world problem solving
* CRUD-style operations

---

## 🚀 Future Enhancements

The project can be further improved by adding:

* 🗄️ Database integration using MySQL
* 🌐 Web-based interface
* 🔐 User authentication and authorization
* 💳 Online payment integration
* 📧 Email notifications
* 📱 Responsive frontend
* 📊 Admin dashboard
* 📈 Rental analytics and reports
* 🔎 Advanced car search and filtering
* ☁️ Cloud deployment

---

## 👨‍💻 Author

**Om Keshari**

B.Tech – Computer Science & Engineering (Data Science)
JSS Academy of Technical Education, Noida

### Connect With Me

* GitHub: `https://github.com/omkeshari245`
* LinkedIn: Add your LinkedIn profile here

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a **⭐ Star** on GitHub.

---

## 📄 License

This project is created for **educational and learning purposes**.
