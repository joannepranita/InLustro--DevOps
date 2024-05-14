**Hiring Management System**

**Description:**

The Hiring Management System is a web application built using Flask, a Python web framework, to streamline the process of managing job applications, conducting tests, and evaluating candidates. This system allows users to register, log in, take tests, and view test results.

**Integration of HTML Templates:**

To integrate HTML templates into the Flask application, follow these steps:

1. **Create HTML Files:** Create HTML files for each route using Flask's `render_template` function. The following HTML files are required:

   - `registration_form.html`
   - `registration_result.html`
   - `login_form.html`
   - `welcome.html`
   - `test_options.html`
   - `aptitude_test.html`
   - `programming_test.html`
   - `results.html`

2. **Modify Routes:** Modify the routes in the Flask application to render these HTML templates. Ensure that the HTML templates are placed in a directory named `templates` in the same directory as your Python script.

**Usage:**

1. **Registration Form:**
   - Access the registration form by navigating to the root URL (`/`).
   - Fill in the required details and submit the form.

2. **Login:**
   - Access the login form by navigating to `/login`.
   - Enter the username and password to log in.

3. **Tests:**
   - Choose the type of test (Aptitude or Programming) from the test options page (`/test`).
   - Take the test by following the instructions on the respective test pages (`/aptitude_test` or `/programming_test`).

4. **View Results:**
   - View the test results by navigating to `/results`.
   - Results will be displayed for the logged-in user.

**Dependencies:**

- Flask
- SQLite3 (for database operations)
- Random (for generating random data)

**Installation:**

1. Install Flask using pip:
   ```
   pip install Flask
   ```

2. Ensure SQLite3 is installed.

3. Clone the project repository:
   ```
   git clone <repository_url>
   ```

4. Run the Flask application:
   ```
   python app.py
   ```

**Contributing:**

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request.

**License:**

This project is licensed under the [MIT License](LICENSE).
