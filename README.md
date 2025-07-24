Hi! Welcome to FinMark's Network Monitoring Dashbdard: Netmonitor
A network monitoring dashboard built with Django :)
Here's how it works:
Step 1: Clone the Repo
git clone https://github.com/PMpanganiban/PTMS2.git
cd PTMS2

Step 2: Set Up the Django Project
python -m venv venv
venv\Scripts\activate   # For Windows
# source venv/bin/activate  # For Mac/Linux
cd netmonitor
python manage.py migrate
python manage.py runserver

Then open your browser and go to:
http://127.0.0.1:8000/
