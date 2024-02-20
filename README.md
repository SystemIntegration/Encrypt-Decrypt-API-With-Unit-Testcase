# .NET 6.0 String Encryption/Decryption APIs

## Description

This project provides two secure APIs for string encryption and decryption within a .NET 6.0 application:

- **EncryptString(string plaintext):** Takes the plaintext string as input and returns the encrypted string using a built-in or pre-configured key for security.
- **DecryptString(string cipherText):** Takes the encrypted string and the original encryption key as input and returns the decrypted plaintext string.

## Prerequisites

- .NET 6.0 SDK installed on your machine
- Visual Studio or your preferred IDE

## Project Setup

1. Clone the repository:

    ```bash
    git clone ssh://git@192.168.0.106:28039/github-demo/dotnet/encrypt-decrypt-api-with-unit-testcase.git
    ```

2. Install dependencies:

    ```bash
    cd your-project-directory
    dotnet restore
    ```

## Running the APIs

1. **Build and Run:**
   - Use `dotnet build` to build the project.
   - Then, run the application with `dotnet run`.

2. **Access Swagger:**
   - Once the application is running, open your browser.
   - Navigate to `http://localhost:5000/swagger/index.html` or `http://localhost:5001/swagger/index.html`.

3. **Using the API:**
   - **Encryption:**
        - Input the plaintext string that you want to encrypt.
   - **Decryption:**
        - Input the following parameters:
            - `cipherText`: This parameter should be a string representing the encrypted text that you want to decrypt. It's typically a Base64-encoded string.
   - In Swagger, you'll see endpoints for encryption and decryption.
   - Click on an endpoint to expand it.
   - Input the required data (plaintext for encryption or ciphertext for decryption).
   - Click "Try it out" and then "Execute" to see the result.


## Additional Notes

- Ensure sensitive information is not included in plaintext before encryption.
- For decryption, ensure the correct ciphertext and corresponding encryption key are provided for accurate results.


## Contributions

Welcome enhancements! Share feedback, submit pull requests, or raise issues on the project's GitLab repository.


