# Guess the Painter

A full-stack website that uses machine learning to guess the impressionist painter of a painting. Users can upload a picture of a painting, and the system will predict the likely painter from a set of options, such as Da Vinci, Frida Kahlo, Henri Matisse, etc.

## Features

- **Image Upload:** Users can upload images of paintings.
- **Painter Prediction:** The system predicts the likely painter using machine learning models.
- **User Interface:** A clean and intuitive user interface for a seamless experience.
- **Full Stack:** The project incorporates both frontend and backend components.

### Example Images:

<img src="/website.png" alt="Image Upload" width="300" height="200">
*Website interface(developed on react.js)*

<img src="/webiste_result.png" alt="Painter Prediction" width="300" height="200">
*Painter Prediction*



## Project Structure

- **.vs:** Visual Studio Code settings.
- **frontend:** Frontend code.
- **models:** Machine learning models used for prediction.
- **node_modules:** Node.js dependencies.
- **training:** Code or data related to model training.
- **README.md:** Project documentation.
- **models.config.pbtxt:** Configuration file for machine learning models.
- **package-lock.json:** Dependency lock file.
- **package.json:** Node.js project configuration.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/KaizenGirl1111/guess-the-painter.git
    cd guess-the-painter
    ```

2. Install dependencies:

    ```bash
    # For frontend
    cd frontend
    npm install

    # For backend
    ## backend developed on fast-api
    http://localhost:8000/docs for swagger UI or test the backend on postman
    ```

3. Run the application:

    ```bash
    # For frontend
    cd frontend
    npm start
    ```

4. Open the application in your web browser.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these guidelines:

- Fork the repository.
- Create a new branch.
- Make your changes and commit them.
- Push the changes to your fork.
- Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to enhance and customize this template according to the specifics of your project. Include information about dependencies, deployment, or any other relevant details.
