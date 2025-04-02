# Personal Project Showcase (Flask Web App)

This is a simple Flask web application designed to showcase your personal projects in a visually appealing manner. It features an animated dark background and clean project displays.

## Features

* **Visually Appealing Design:**
    * Dark, animated gradient background.
    * Shiny, modern project item displays with a glass effect.
    * Clean and readable project titles and descriptions.
* **Dynamic Project Display:**
    * Projects are loaded from a Python list, making it easy to add or modify project information.
    * Images are displayed alongside project details.
* **Flask and Jinja2:**
    * Built using the Flask web framework for Python.
    * Jinja2 templating engine for dynamic HTML rendering.

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [your-repository-url]
    cd [repository-directory]
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    ```

3.  **Activate the virtual environment:**

    * **Windows:**

        ```bash
        venv\Scripts\activate
        ```

    * **macOS/Linux:**

        ```bash
        source venv/bin/activate
        ```

4.  **Install Flask:**

    ```bash
    pip install Flask
    ```

5.  **Run the application:**

    ```bash
    python app.py
    ```

6.  **Open your web browser and go to `http://127.0.0.1:5000/`.**

## Project Structure
├── app.py          # Flask application
├── templates/
│   └── index.html  # HTML template
├── venv/           # Virtual environment (if created)
└── README.md       # This file

## Customization

* **Adding Projects:** Modify the `projects` list in `app.py` to add or change project information.
* **Images:** Place your project images in the same directory as `app.py` or in a subdirectory, and update the `image` paths in the `projects` list.
* **Styling:** Customize the CSS in `templates/index.html` to change the appearance of the page.
* **Advanced features:** you can add a database to store project data, and allow for user input.

## Future Improvements

* Implement a database to store project data persistently.
* Add user input to add/edit projects.
* Improve responsiveness for different screen sizes.
* Add more advanced CSS animations.

