# Email Generator with Google Gemini AI

This is a Spring Boot project that generates replies to emails using the Google Gemini AI API.

## Features

- Reads incoming emails
- Generates AI-based responses using Google Gemini AI

## Technologies Used

- **Spring Boot** - Backend framework
- **Google Gemini AI** - AI-based email response generation
- **Maven** - Dependency management

## Prerequisites

Ensure you have the following installed:

- Java 17+
- Maven
- A Google API key for accessing Gemini AI
- Email credentials (SMTP setup)

## Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/YashUkhare/Email-Generator.git
   cd Email-Generator
   ```
2. Configure application properties:
   - Update `src/main/resources/application.properties` with your email credentials and Google API key.
3. Build and run the project:
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```

## Usage

- The application listens for incoming emails.
- It generates responses using Google Gemini AI.

## Deployment

You can deploy the project on a cloud server or containerize it using Docker.

## Contributing

Feel free to submit issues or pull requests to improve the project.

## License

This project is open-source under the MIT License.

## Contact

For any queries, reach out at ukhareyash2001\@gmail.com.

