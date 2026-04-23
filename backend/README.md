# Backend
The backend is built using Django and provides the API for the Coda application.

## Setup
Clone the repository: <br>
git clone https://github.com/Thomas-Onnes/Coda.git <br>

Go to the correct directory: <br>
cd Coda/backend

Create virtual environment: <br> <br>
Windows: <br>
python -m venv .venv <br>
.venv\Scripts\activate <br>


Mac/Linux: <br>
Python3 -m venv .venv <br>
source .venv/bin/activate

Install dependencies: <br>
pip install -r requirements.txt

### Run the server
Python manage.py runserver

### Apply database migrations
python manage.py migrate