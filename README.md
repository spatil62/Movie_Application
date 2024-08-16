Movie Management Application

Overview

The Movie Management Application is an advanced Spring Boot-based platform that revolutionizes how movie data and reviews are handled. Designed with efficiency and scalability in mind, this application harnesses the power of MongoDB to manage movie-related information seamlessly. It provides a robust RESTful API that allows for effortless management of movie entries and user reviews, making it an essential tool for modern media applications.

Features

Dynamic Movie Management: Effortlessly create, retrieve, and update movies, including detailed metadata such as IMDb ID, release dates, genres, and multimedia links.
Integrated Review System: Streamline the process of adding reviews to movies, with real-time updates that enrich movie profiles and enhance user engagement.
Comprehensive Data Access: Retrieve comprehensive lists or specific details of movies, with optimized endpoints for quick and efficient access.
Key Components

Movie Entity: The heart of the application, storing extensive movie details and linking reviews dynamically. This entity supports advanced querying and data retrieval.
Review Entity: Designed to capture user feedback and seamlessly integrate with movie records, providing valuable insights and enhancing movie profiles.
MovieController: The gateway for all movie-related API requests. It manages interactions, ensuring that requests for movie data are handled swiftly and accurately.
ReviewController: Facilitates the creation of reviews and ensures they are correctly associated with the appropriate movies, enriching the overall movie data.
MovieRepository: A powerful MongoDB repository that supports complex queries and ensures reliable data operations.
ReviewRepository: Manages review data with precision, enabling efficient storage and retrieval of user feedback.
MovieService: Central to business logic, handling operations related to movie management and ensuring that data is processed efficiently.
ReviewService: Manages the creation and association of reviews, maintaining consistency and integrity within movie records.
Technologies Used

Spring Boot: A leading framework for building robust and scalable RESTful APIs, simplifying configuration and deployment.
MongoDB: A flexible NoSQL database that provides high performance and scalability for managing complex movie and review data.
Lombok: Streamlines code by reducing boilerplate, making data models clean and manageable.
Usage

Experience the power of seamless movie and review management through our intuitive API:

Movies
Retrieve a full catalog or specific movie details with ease, leveraging advanced querying capabilities.
Reviews
Add insightful reviews to movies, enhancing their profiles and providing valuable user feedback.
