# Go Boilerplate 

A ready to use template for GO applications that follows clean architecture principles.

## Project Structure

* **cmd:** Contains the main entry point for the command-line application, with a placeholder function.
    * **cli** Contains the command-line interface (CLI). The `main.go` file serves as the entry point for the CLI application.
* **internal:** Houses the core application logic.
    * **domain:**  Defines core entities and models.
    * **repositories:**  Defines interfaces for interacting with external data sources.
    * **usecases:**  Implements business logic and coordinates interactions with repositories.
    * **interfaces:**  Provides concrete implementations for repository interfaces.
* **pkg:**  Contains reusable utility functions.

## Usage

1. **Prerequisites:**
    * A Go development environment (https://golang.org/doc/install)

2. **Get the code:**
   ```bash
   git clone [https://github.com/Sharper-Flow/go-boilerplate.git](https://github.com/Sharper-Flow/go-boilerplate.git)
    ```

3. **Configuration**
    * Create a .env file in the project root to store any keys or tokens (see .env.example for a template)

4. **Build and Run**
   ```bash
   go build ./cmd/cli
   ./cli <args>
    ```

