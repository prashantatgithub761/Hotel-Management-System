# 🏨 Hotel Management System

A Spring Boot–based Hotel Management System that provides REST APIs to manage hotel information. The application follows a clean layered architecture using Controller, Service, Entity, and DTO patterns and demonstrates inter-service communication using RestTemplate.

---

## 📌 Features

- Create and fetch hotel details
- Update hotel address using DTO
- RESTful APIs with clean request and response handling
- Uses DTO pattern to avoid exposing entity directly
- Demonstrates inter-service communication using RestTemplate
- Clean and maintainable layered architecture

---

## 🛠 Tech Stack

- Language: Java  
- Framework: Spring Boot  
- Architecture: REST APIs, Controller–Service pattern  
- Concepts: OOPs, DTO Pattern, Dependency Injection  
- Communication: RestTemplate  

---

## 📂 Project Structure

src/main/java  
├── controller  
│   └── HotelController.java  
├── service  
│   └── HotelService.java  
├── dto  
│   ├── HotelDTO.java  
│   └── UpdateHotelAddressDTO.java  
├── entity  
│   └── Hotel.java  
├── util  
│   └── RestTemplateCommunicator.java  
└── Application.java  

---

## 🔁 Application Flow

1. Client sends HTTP request to HotelController  
2. Controller forwards request to HotelService  
3. Service layer processes business logic  
4. DTOs are used for request/response mapping  
5. Response is returned to client in JSON format  

---

## 📮 Sample API Endpoints

Create Hotel  
POST /hotels  

Get All Hotels  
GET /hotels  

Update Hotel Address  
PUT /hotels/address  

(Note: Endpoints may vary based on implementation)

---

## 🚀 How to Run the Project

1. Clone the repository  

2. Open the project in any Java IDE (IntelliJ / Eclipse / VS Code)

3. Ensure Java and Maven are installed

4. Run the application  
   mvn spring-boot:run  

   OR run the main application class directly from IDE

5. Test APIs using Postman

---

## 🎯 Learning Outcomes

- Strong understanding of Spring Boot REST APIs  
- Practical usage of DTO pattern  
- Experience with layered backend architecture  
- Understanding of RestTemplate for service communication  

---

## 📌 Future Enhancements

- Add database integration using JPA and MySQL  
- Implement validation and exception handling  
- Add Swagger for API documentation  
- Secure APIs using Spring Security and JWT  

---
