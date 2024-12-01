# IntelliFinance

IntelliFinance is a personal finance tracker built with Django. It helps you manage your expenses, set savings goals, and visualize your financial habits with easy-to-read charts and reports.

## Features
- Add and categorize income and expenses
- Set and monitor savings goals
- View your financial history and summaries
- Visualize your spending with charts
- Download your financial summary as a PDF
- User authentication (register, login, logout)

## Getting Started

### Prerequisites
- Python 3.11+
- pipenv (for dependency management)

### Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/guptapratykshh/Automation.git
   cd Automation
   ```
2. **Install dependencies:**
   ```sh
   pip install pipenv
   pipenv install
   pipenv shell
   ```
3. **Apply migrations:**
   ```sh
   python manage.py migrate
   ```
4. **Run the development server:**
   ```sh
   python manage.py runserver
   ```
5. **Open your browser:**
   Visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Usage
- Register a new account or log in.
- Add your income and expenses.
- Set a savings goal and track your progress.
- View charts and download your financial summary as a PDF.

## Project Structure
- `expenses/` - Main app for expense tracking
- `finance_tracker/` - Project settings and configuration
- `templates/` - HTML templates for the frontend
- `manage.py` - Django management script

## License
This project is open source and available under the [MIT License](LICENSE).

---

If you have any questions or suggestions, feel free to open an issue or submit a pull request.
