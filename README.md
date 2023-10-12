# Django CRUD & Mysql
## Requirements

- Python 3.x
- Django (recommended version)
- MySQL (or any other database you wish to use)
- (Optional) Virtualenv for virtual environments

## Environment Setup

1. **Clone the Repository:**
2. **Create a Virtual Environment (Optional but Recommended):**
```python
python -m venv
source venv/bin/activate
```
3. **Install Dependencies:**
```python
pip install -r requirements.txt
```
4. **Configure the Database:**
- Create a MySQL database and update the configuration in `settings.py`.
- Run migrations:
```python
python manage.py migrate
```

5. **Start the Development Server:**
```python
python manage.py runserver
```
6. **Access the Application:**
Visit `http://localhost:8000` in your web browser.

## Contributing

If you want to contribute to this project, follow these steps:

1. Fork the project
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Make your changes and commit them (`git commit -m 'Add new feature'`)
4. Push the branch (`git push origin feature/new-feature`)
5. Open a pull request on GitHub

## Util commands
- Create a migration file after to create a new model
```python
python manage.py makemigrations
```
- Create a superuser
```python
python manage.py createsuperuser
```