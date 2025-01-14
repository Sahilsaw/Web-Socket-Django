Steps to Run the Project:

Install Dependencies
Run the following command to install all required dependencies from the requirements.txt file:
pip install -r requirements.txt

Apply Database Migrations
Ensure you are in the directory containing the manage.py file, then run:
python manage.py migrate

Start the Development Server
While in the same directory as manage.py, start the server by executing:
python manage.py runserver

Once the server is running, you can access the application. Create an account and log in. Open the application in multiple browsers using different accounts to initiate a chat. Use the "Users" button to view active users and start chatting.
