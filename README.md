# Kitabi_Kida

Kitabi_Kida is an advanced e-commerce application designed for an online bookstore. Built using .NET and Angular 18, this platform leverages SQL Server as the backend database. The application allows users to browse, and manage books online, offering an intuitive, secure, and seamless user experience.

## Development Approach

Our development approach focused on leveraging modern frameworks and best practices to ensure a scalable and maintainable solution. We followed a layered architecture to keep the concerns well-separated and ensure modularity.

### Backend Development
We adopted the Entity Framework Core (EF Core) with the DB-first approach to streamline database interaction. This allowed us to quickly generate models based on the existing database schema and focus on business logic.

### Authorization
For securing API endpoints, we implemented policy-based authorization using JSON Web Tokens (JWT), ensuring robust access control for users and administrators.

### Frontend Development
Angular 18 was used to build a rich, responsive front-end interface. We utilized Angular Material for consistent UI components and followed best practices in Angular development such as lazy loading for components and reactive forms for form handling.

### API Documentation
Swagger was integrated to automatically generate API documentation, helping both developers and stakeholders understand the available endpoints and their usage.

---

## Concepts Covered

### .NET

- Web API created using EF Core DB-first approach
- Policy-based Authorization using JWT
- Repository pattern for data management
- Dependency Injection for improved testability and maintainability
- Swagger integration for API documentation

### Angular

- Angular Material for UI components
- Routing & Navigation for application flow
- Auth guards for route protection
- Standalone components for modular development
- Lazy loading of components for better performance
- HTTP Interceptors for handling HTTP requests and responses
- Reactive forms for dynamic form handling
- Inbuilt and custom form validation
- Pipes for transforming data in templates

---

## Challenges We Faced: Key Obstacles During Development

1. **Complex API Integration**: The interaction between Angular and the .NET Web API was one of the early challenges. We had to ensure that the APIs were well-defined and secure, especially when integrating JWT-based authentication. We also faced difficulties in synchronizing HTTP requests from Angular to the backend, particularly with data binding and handling errors.
  
2. **Database Structure**: With EF Core’s DB-first approach, managing complex relationships and large datasets in SQL Server proved challenging, especially when optimizing queries to enhance performance and prevent slow response times.

3. **Authentication and Authorization**: Implementing JWT-based policy authorization was complex, as we needed to balance flexibility (allowing various roles like user, admin, etc.) with security. Ensuring that all API calls were securely validated for each user's session required attention to detail.

4. **Form Validation**: Building dynamic forms with custom validation logic was tricky, especially when dealing with real-time validation and error handling. Angular’s reactive forms helped but posed challenges in ensuring smooth user experience during form submission and validation errors.

---

## Key Achievements: Milestones We're Proud Of

1. **Seamless Authentication Flow**: We successfully implemented a secure authentication system using JWT, providing a smooth and secure login experience for users and administrators.
   
2. **Optimized Performance**: By utilizing Angular’s lazy loading and Angular Material's performance-focused components, we achieved faster page load times and a more responsive user interface.
  
3. **Comprehensive API Documentation**: With Swagger integrated into our development process, we created well-documented and easily consumable APIs, enabling clear communication between the front-end and back-end teams.
  
4. **Responsive Design**: The use of Angular Material and responsive web design techniques allowed us to deliver a mobile-friendly, adaptive interface that functions smoothly across different devices and screen sizes.
  
5. **Error-Free Forms**: The implementation of reactive forms with custom validation logic ensured that the user inputs were properly validated, and real-time feedback was provided, enhancing the overall user experience.

---

## What We Learned: Insights and Takeaways

1. **Importance of Modular Design**: The repository pattern and dependency injection helped decouple concerns, making the system easier to maintain, test, and extend in the future.
   
2. **The Power of Angular Material**: By leveraging Angular Material, we were able to save development time and ensure that the application had a consistent and modern user interface without needing to design components from scratch.

3. **API Security**: Implementing JWT-based authorization taught us the importance of securing endpoints and properly handling tokens to avoid vulnerabilities such as token theft or misuse.

4. **Database Optimization**: The DB-first approach with EF Core highlighted the significance of well-structured database schemas and the need for query optimization, especially when dealing with large-scale data.

---

## Future Vision: What's Next

1. **Enhanced Search Functionality**: In the future, we plan to enhance the search and filtering capabilities, allowing users to filter books based on various criteria like genre, author, or publication date.

2. **User Reviews and Ratings**: Adding a feature for user-generated reviews and ratings will allow users to interact more with the platform, creating a community-driven bookstore.

3. **Mobile App Version**: Although Kitabi_Kida is a web application, we are considering a mobile version to enhance accessibility, using either Angular with Ionic or a native mobile development approach.
   
---

## Prerequisites

- Visual Studio 2022
- SQL Server
- .NET Core SDK 8.0 or higher
- Node.js V18.0 or higher
