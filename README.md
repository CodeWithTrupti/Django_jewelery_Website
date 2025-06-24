 💍 Django Jewelry Website

A fully functional jewelry e-commerce website built using Django, designed to showcase beautiful jewelry products with user-friendly navigation and an admin panel for product management.


✨ Features

- Jewelry product listing and details page  
- Admin dashboard to manage inventory  
- Responsive front-end with HTML, CSS, and Bootstrap  
- Django-powered back-end with dynamic content  
- User authentication 


🔧 Technologies Used

- **Backend**: Python, Django  
- **Frontend**: HTML5, CSS3, Bootstrap  
- **Database**: SQLite3 (default in Django)  


🚀 Setup Instructions

To run this project locally on your machine:

# 1. Clone the repository
git clone https://github.com/CodeWithTrupti/Django_jewelery_Website.git
cd Django_jewelery_Website

# 2. Create and activate a virtual environment
python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate

# 3. Install required dependencies
pip install -r requirements.txt

# 4. Apply migrations
python manage.py migrate

# 5. Create a superuser for admin access
python manage.py createsuperuser

# 6. Run the server
python manage.py runserver
