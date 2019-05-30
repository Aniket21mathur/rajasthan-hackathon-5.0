# Team: THE SPRT

This project is our submission for the Rajasthan Hackathon 5.0. This is site which promotes E-Governance and facilitates communication between the government and the citizens to great extent.

### Features: 
* A dashboard showing user details as well as Notices and Circulars. This is a dynamic dashboard.
* A Forum for discussion on issues.
* A Job Portal where the user can upload their resumes(as pdf or images) and the he/she is provided with the specific keywords to related to his professional expertise (to be used in job search).
* A Feedback Form which automatically analyses the sentiment of the feedback/complaint and places tags for urgent attention by the government. The feedback/complaint is sent as an email to the respective authority.
* A notices and information parser which in its beta phase presently.

### Setup:
* First make sure you are in a Python3 Virtual Environment.
* Open up four terminals.
* In one terminal, open up the root directory, and run `php -S localhost:4000` .
* In another terminal, open up `feedback` directory from root directory and run `python3 manage.py runserver`.
* In the third terminal navigate to `forum` directory under root and run `php -S localhost:1234`.
* In the fourth terminal, navigate to `backend` under root directory and run `python3 main.py runserver`.
* Open up your favourite browser, open `localhost:4000`, and enjoy! 
