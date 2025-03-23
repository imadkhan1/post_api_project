Post API Project
Post API Project is a Flutter application that demonstrates how to make HTTP POST requests using the http package. The app includes a simple login screen where users can input their email and password to simulate a login process.

Features
Login Screen: A user-friendly interface with email and password input fields.

HTTP POST Request: Sends login data to a mock API endpoint (https://reqres.in/api/register).

Response Handling: Displays success or failure messages based on the API response.

Token Display: Prints the token received from the API on successful login.

Project Structure
bash
Copy
Edit
lib/
├── main.dart          # Entry point of the application
├── login_screen.dart  # Login screen with API integration
Getting Started
Prerequisites
Ensure you have the following installed:

Flutter SDK (version 3.5.4 or higher)

Dart SDK

A code editor like Visual Studio Code or Android Studio

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-repo/post_api_project.git
Navigate to the project directory:

bash
Copy
Edit
cd post_api_project
Install dependencies:

bash
Copy
Edit
flutter pub get
Running the App
Connect a physical device or start an emulator.

Run the app:

bash
Copy
Edit
flutter run
Dependencies
This project uses the following dependencies:

http: ^1.3.0 - For making HTTP requests.

modal_progress_hud_nsn: ^0.5.1 - For showing a loading indicator during API calls.

cupertino_icons: ^1.0.8 - For iOS-style icons.

API Endpoint
The app uses the following mock API endpoint for demonstration purposes:

URL: https://reqres.in/api/register

How It Works
The user enters their email and password in the login form.

On tapping the "Login" button, the app sends a POST request to the API endpoint with the entered credentials.

The app handles the API response:

If the response status code is 200, it prints the token and displays a success message.

Otherwise, it displays a failure message.

Screenshots
Add screenshots of the login screen here.

License
This project is licensed under the MIT License. See the LICENSE file for details.
