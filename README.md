
# Django Blog Project

This is a Django-based blog application that uses `django-taggit` for tagging blog posts. The project includes basic blog functionalities and a sitemap for SEO.

## Features

- Blog post creation, editing, and deletion.
- Tagging of blog posts using `django-taggit`.
- Sitemap for posts and tags.
- Basic user authentication and admin interface.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- Git
- Virtualenv (optional but recommended)

### Step 1: Clone the Repository

Clone the repository from GitHub to your local machine.

```bash
git [clone https://github.com/your_username/your_repository.git](https://github.com/tarunkeshukumar/django_blog_app/)
cd blog_app
```

### Step 2: Create and Activate a Virtual Environment

Create a virtual environment to isolate the project dependencies.

```bash
# On macOS/Linux
python3 -m venv my_env
source my_env/bin/activate

# On Windows
python -m venv my_env
my_env\Scripts\activate
```

### Step 3: Install the Dependencies

Install the required dependencies from the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

### Step 4: Set Up Environment Variables

Create a `.env` file in the project root directory to store environment-specific variables such as the Django secret key, database credentials, etc.

Example `.env` file:

```plaintext
SECRET_KEY=your_secret_key
DEBUG=True
DATABASE_URL=your_database_url
```

### Step 5: Apply Migrations

Run the database migrations to set up the database schema.

```bash
python manage.py migrate
```

### Step 6: Create a Superuser

Create a superuser account to access the Django admin interface.

```bash
python manage.py createsuperuser
```

### Step 7: Run the Development Server

Start the development server to run the project locally.

```bash
python manage.py runserver
```

## Usage

Once the server is running, you can access the application at [http://127.0.0.1:8000/](http://127.0.0.1:8000/). The Django admin interface is available at [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/).

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please feel free to contact me at [tarunkeshukumar@gmail.com].
