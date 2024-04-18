

1. **Python Code**:
   - Imports the necessary modules (`render_template`, `Flask`, `request`).
   - Creates a Flask application object named `app`.
   - Defines a route `/login/<username>/<password>` that takes `username` and `password` as parameters and checks if they are both "admin". If so, it returns a welcome message; otherwise, it returns a login failure message.
   - Defines a route `/` that renders the `login.html` template.
   - Defines a route `/validate` that handles form submission via POST method. It checks if the entered username and password are "admin" and "admin" respectively. If correct, it returns a welcome message; otherwise, it returns a login failure message.
   - Finally, it runs the Flask app if the script is executed directly (`__name__ == '__main__'`).

2. **HTML Template (login.html)**:
   - Contains a form with fields for username and password.
   - The form submits data to the `/validate` route via POST method.
   - Includes basic HTML structure, a title, and a link to an external CSS file (`main.css`).
![Screenshot 2024-04-18 085940](https://github.com/Darshansures/Darshan-devtern/assets/167393078/74dd6e59-16f6-4a3f-9a7f-d921551aabd0)
![Screenshot 2024-04-18 085934](https://github.com/Darshansures/Darshan-devtern/assets/167393078/92b5950e-1dc2-46ee-b46b-3df10f8b0ebb)
![Screenshot 2024-04-18 085918](https://github.com/Darshansures/Darshan-devtern/assets/167393078/61dc8d56-6246-4950-a5ee-3e0b5c8e738a)
![Screenshot 2024-04-18 085911](https://github.com/Darshansures/Darshan-devtern/assets/167393078/5ae06c83-4130-4959-81ad-922cfe051215)
