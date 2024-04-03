Django Poll App
This is a Django web application for conducting polls. Users can create polls, vote on existing polls, and view the results of polls. The application is built using Django, a high-level Python web framework.

Features
Poll Creation: Users can create new polls by specifying a question and adding multiple choices for answers.
Voting: Registered users can vote on the available choices for each poll.
Results: Users can view the results of polls in real-time.
Authentication: User authentication is implemented to ensure that only registered users can create new polls or vote on existing ones.
Admin Interface: Administrators have access to an admin interface where they can manage polls, including adding, editing, or deleting them.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your_username/django-poll-app.git
Navigate to the project directory:

bash
Copy code
cd django-poll-app
Install dependencies:

Copy code
pip install -r requirements.txt
Run migrations:

Copy code
python manage.py migrate
Create a superuser (an admin account):

Copy code
python manage.py createsuperuser
Start the development server:

Copy code
python manage.py runserver
Access the application at http://localhost:8000/ in your web browser.

Usage
Creating Polls: Log in as an admin and go to the admin interface (http://localhost:8000/admin). Then, you can add new polls and their choices.
Voting: Regular users can browse the available polls on the homepage and vote for their preferred choices.
Viewing Results: After voting, users can see the results of the polls, including the percentage of votes for each choice.
Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Make your changes and commit them (git commit -am 'Add new feature').
Push your branch (git push origin feature/new-feature).
Create a pull request.

Credits
This project was created by Alicia Campbell.
https://github.com/AliciaCamp/Poll-App.git

Contact
For any inquiries or support, please email aliciacampbell4990@gmail.com.

Acknowledgments
Special thanks to the Django community for their excellent documentation and resources.
