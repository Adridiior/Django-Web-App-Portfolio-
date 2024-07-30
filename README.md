
# Django-Web-App-Portfolio

Django-Web-App-Portfolio is a web application built using Django. This project serves as a portfolio to showcase various web development projects and skills.

## Features

- **Project Showcase**: Display various web development projects.
- **Blog**: Share articles and insights.
- **Contact Form**: Allow visitors to get in touch via a contact form.
- **Authentication**: User login and registration functionality.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Adridiior/Django-Web-App-Portfolio-.git
   cd Django-Web-App-Portfolio
   ```

2. Create a virtual environment and activate it:
   ```sh
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Apply the migrations:
   ```sh
   python manage.py migrate
   ```

5. Create a superuser to access the admin panel:
   ```sh
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```sh
   python manage.py runserver
   ```

## Usage

- **Home Page**: Overview of the portfolio and recent blog posts.
- **Projects**: Browse the projects section to see detailed descriptions and links.
- **Blog**: Read articles and leave comments (if enabled).
- **Contact**: Use the contact form to send messages.

## Project Structure

- **myportfolio/**: Main project directory.
- **projects/**: App for managing and displaying projects.
- **blog/**: App for managing blog posts and comments.
- **contact/**: App for handling contact form submissions.
- **static/**: Directory for static files.
- **templates/**: Directory for HTML templates.
- **requirements.txt**: List of dependencies.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Credits

- Developed by Adriano Di Iorio
- Built with [Django](https://www.djangoproject.com/)
