# 📚 Student Management System

A Spring Boot application for managing student records with a RESTful API.

## ✨ Features

- 📝 Create, read, update, and delete student records
- 🔄 RESTful API endpoints for all CRUD operations
- 💾 In-memory H2 database
- 🛢️ Spring Data JPA for data access
- 🌐 Spring Web for REST endpoints

## 📋 Prerequisites

- ☕ Java 17 or higher
- 🧰 Maven 3.6.3 or higher
- 💻 An IDE (IntelliJ IDEA, Eclipse, or VS Code)

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone [your-repository-url]
   cd student-management
   ```

2. **Build the application**
   ```bash
   mvn clean install
   ```

3. **Run the application**
   ```bash
   mvn spring-boot:run
   ```

## 🔌 API Endpoints

- `GET /api/students` - 📋 Get all students
- `GET /api/students/{id}` - 🔍 Get a student by ID
- `POST /api/students` - ➕ Create a new student
- `PUT /api/students/{id}` - ✏️ Update a student
- `DELETE /api/students/{id}` - ❌ Delete a student

## 💾 Database

The application uses an in-memory H2 database by default. You can access the H2 console at:
- 🔗 URL: http://localhost:8080/h2-console
- 🔑 JDBC URL: jdbc:h2:mem:studentdb
- 👤 Username: sa
- 🔒 Password: (leave empty)

## 📂 Project Structure

```
src/
├── main/
│   ├── java/com/example/student_management/
│   │   ├── controller/    # REST controllers
│   │   ├── entity/        # JPA entities
│   │   ├── repository/    # Data repositories
│   │   ├── service/       # Business logic
│   │   └── StudentManagementApplication.java  # Main application class
│   └── resources/
│       ├── application.properties  # Application configuration
│       └── static/       # Static resources
└── test/                 # Test files
```

## 🤝 Contributing

1. 🍴 Fork the repository
2. 🌱 Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔄 Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
