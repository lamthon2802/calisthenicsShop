Calisthenics Shop
A web application for selling calisthenics workout gear, built with Spring Boot, Thymeleaf, and SQL Server.

Features
User registration, login, and profile management


Product catalog with categories and subcategories


Product attributes (size, color)


Shopping cart and wishlist


Order management and payment details


Soft delete for data integrity


Activity log to track user actions


Responsive UI with Thymeleaf templates



Technologies Used
Java 17+


Spring Boot 3.x


Spring Data JPA (Hibernate)


Spring Security (optional for authentication)


Thymeleaf (server-side rendering)


SQL Server (database)


Maven (build tool)



Database
The database schema uses soft delete flags (is_deleted) to keep data history.
Main tables:
users


addresses


categories & sub_categories


products & product_attributes & products_skus


wishlist


cart & cart_item


order_details & order_item


payment_details


activity_logs



Setup & Run
Prerequisites
Java JDK 17 or later


SQL Server (with database calisthenicsShop)


Maven 3.x



DBdiagram:https://dbdiagram.io/d/shop-682a0f6a1227bdcb4ed86857
