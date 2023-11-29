# Assignment-6-Ecart-Rest-api
This project is a simple Spring Boot application implementing RESTful APIs for an E-cart platform. It includes features such as displaying products, managing a shopping cart, and more.
 
## Features
1.Find all products 
2.Find/filter all products whose price is in the givn range(min,max)
3.Display all categories only
4.Display all categories with Brand names
5.Display all categories with Brand, and displayed brands products
6.add a product to the cart for a specified user
7.display cart items of a specified user
8.Run on localhost network
 
## Prerequisites
- Java 11 or higher
- Maven or Gradle (for building the project)
- Preferred IDE (e.g., IntelliJ, Eclipse)
 
## Getting Started
 1. Clone the repository:
 git clone https://github.com/your-username/your-spring-boot-project.git
   cd your-spring-boot-project

## Build and run the project
For Maven
mvn spring-boot:run
 For Gradle
./gradlew bootRun
Access the APIs locally: http://localhost:8080

## Endpoints
.GET /api/products: Retrieve all products.
.GET /api/products/filter?min={min}&max={max}: Filter products within a given price range.
.GET /api/products/categories: Retrieve all categories.
.GET /api/products/categories-with-brands: Retrieve all categories with brand names.
.GET /api/products/categories-with-brands-and-products: Retrieve all categories with brand names and associated products.
.POST /api/cart/add-to-cart/{userId}/{productId}/{quantity}: Add a product to the cart for a specific user.
.GET /api/cart/user-cart/{userId}: Retrieve cart items for a specific user

## Configuration
We can configure our preferred database in the application.properties. 
