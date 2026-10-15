# Airbnb-Clone-Backend


A Spring Boot based backend application for an Airbnb-style booking platform. This project provides REST APIs for user authentication, property management, booking, and payment integration.

---

## 🚀 Features

- User Registration & Login
- JWT Authentication & Authorization
- Property Listing Management
- Booking Management
- PostgreSQL Database Integration
- Stripe Payment Integration
- RESTful APIs
- Spring Data JPA
- Maven Build System

---

## 🛠️ Tech Stack

- Java 17+
- Spring Boot 3
- Spring Data JPA
- Spring Security
- JWT Authentication
- PostgreSQL
- Maven
- Stripe API

---

## 📂 Project Structure

```text
src/
 ├── main/
 │   ├── java/
 │   ├── resources/
 │   └── application.properties
 └── test/
```

---

## ⚙️ Prerequisites

Before running the project, install:

- Java 17 or above
- Maven
- PostgreSQL
- IntelliJ IDEA / VS Code

---

## 🗄️ Database Configuration

Update the database configuration in `application.properties`:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/your_database
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
```

---

## ▶️ Run the Project

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
```

Go to the project folder:

```bash
cd your-repository
```

Run the application:

```bash
./mvnw spring-boot:run
```

or

```bash
mvn spring-boot:run
```

---

## 🔐 Security

The project uses:

- Spring Security
- JWT Authentication
- Role-Based Authorization

**Important:** Do not commit secret keys (JWT secret, Stripe secret, database passwords) to GitHub. Use environment variables or a local configuration file that is excluded from version control.

---

## 📌 Future Improvements

- Email Verification
- Password Reset
- Image Upload
- Reviews & Ratings
- Wishlist
- Admin Dashboard
- Docker Support
- CI/CD Deployment

---

## 👩‍💻 Author

**Pooja Lodhi**

Feel free to contribute or raise issues for improvements.
