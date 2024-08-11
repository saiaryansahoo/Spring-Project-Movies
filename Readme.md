<h1 align="center">Movie Trailer Website - Made with Spring Boot</h1>

Welcome to the world of cinema enthusiasts! This beginner-level project combines the power of Spring Boot, MongoDB, and React to create a seamless Movie Review and Watchlist Application. This platform allows users to explore movie trailers, share their reviews, and curate a personalized watchlist. ❤️

## 🧐 Features

Here are some of the project's best features:

- **Movie Trailers**: Watch trailers of movies directly on the platform for an immersive experience. Enhance user engagement by integrating video playback features.
- **Review and Rating System**: Enable users to submit reviews and ratings for movies. Display average ratings and user reviews to help others make informed decisions.
- **Watchlist Management**: Enable users to create and manage a watchlist of movies they want to watch. Add and remove movies from the watchlist with ease.
- **Backend API**: Develop a RESTful backend API to handle frontend requests and manage data. Ensure proper API documentation for easy integration and collaboration.
- **Testing**: Conduct thorough testing, including unit tests for backend components and integration tests for the entire application.

## 💻 Built with

Technologies used in the project:

- **React**: A popular JavaScript library for building user interfaces. React provides a component-based architecture, making it easy to develop interactive and dynamic frontend applications.
- **Spring Boot**: A Java-based framework that simplifies the development of robust, scalable, and maintainable backend applications. Spring Boot provides a convention-over-configuration approach, reducing the need for boilerplate code.
- **MongoDB**: A NoSQL database that stores data in a flexible JSON-like format. MongoDB is well-suited for projects where data structures may evolve over time, offering scalability and ease of integration.

## 🚀 Installation Steps

Follow these steps to set up the project on your local machine:

### Prerequisites

Make sure you have the following installed on your machine:

- Java 11 or later
- Node.js (which includes npm)
- MongoDB
- Maven

### Backend Setup

1. **Clone the repository**
    ```sh
    git clone https://github.com/saiaryansahoo/Spring-Project-Movies.git
    cd Spring-Project-Movies
    ```

2. **Navigate to the backend directory**
    ```sh
    cd backend
    ```

3. **Build the backend with Maven**
    ```sh
    mvn clean install
    ```

4. **Run the backend**
    ```sh
    mvn spring-boot:run
    ```

The backend server should now be running at `http://localhost:8080`.

### Frontend Setup

1. **Navigate to the frontend directory**
    ```sh
    cd frontend
    ```

2. **Install the dependencies**
    ```sh
    npm install
    ```

3. **Run the frontend**
    ```sh
    npm start
    ```

The frontend should now be running at `http://localhost:3000`.

### MongoDB Setup

1. **Start MongoDB**
    Make sure your MongoDB server is running. By default, it should be running at `mongodb://localhost:27017`.

2. **Database Configuration**
    The application is configured to use a database named `movieDB`. You can change the database name in the `application.properties` file located in the `src/main/resources` directory of the backend.

### Access the Application

Open your web browser and go to `http://localhost:3000` to access the Movie Review and Watchlist Application.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to be, learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🛠️ Testing

Testing is a crucial part of the development process. This project includes:

- **Unit Tests**: Test individual components of the backend.
- **Integration Tests**: Ensure that different components of the application work together as expected.

To run the tests, use the following command in the backend directory:
```sh
mvn test
```


## 📧 Contact

-**Your Name** - saiaryan.sahoo@gmail.com

-**Project Link**: https://github.com/saiaryansahoo/Spring-Project-Movies

