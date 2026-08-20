# AC2 — Manufacturing Production Management System (MES Lite)

Starter repository for the **Manufacturing Production Management System (MES Lite)** project.

This repository intentionally contains only the basic Django project and application structure needed to begin development. The project requirements are provided separately by Neonst.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/neonst-tech/AC2.git
cd AC2
```

### 2. Create and activate a virtual environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run initial Django migrations

```bash
python manage.py migrate
```

### 5. Start the development server

```bash
python manage.py runserver
```

Open `http://127.0.0.1:8000/` in your browser.

## Project Structure

```text
AC2/
├── manufacturing/      # Main Django application
├── config/             # Django project configuration
├── templates/          # Shared HTML templates
├── static/             # Static assets
├── manage.py
├── requirements.txt
└── README.md
```

## Development Notes

- The application uses Django.
- SQLite is configured as the initial development database.
- Bootstrap and the application UI should be added as part of development.
- Application models, production workflows, pages, views, URLs, templates, validation, and business logic are intentionally left for implementation from the project requirements.
- Do not commit the virtual environment or secret configuration files.

## Before Submission

- Test the application from a clean environment.
- Make sure all required pages and navigation work.
- Make sure forms perform appropriate validation.
- Include database migration files.
- Remove unused files and code.
- Add screenshots of the completed application as requested in the project requirements.
