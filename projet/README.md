Project Overview
The Advanced Firewall project is a web application designed to filter incoming and outgoing network traffic based on predefined rules. 
It leverages various design patterns for a maintainable and scalable codebase. 
The project includes functionalities such as login authentication, managing whitelists and blacklists, moving rules between these lists, and checking packet validity.

Objectives
Implement Strategy, Factory, and Singleton design patterns.
Develop strategies for filtering network traffic based on IP addresses, ports, and protocols.
Create a user interface to add rules and filter traffic.

System Requirements
Python 3.12 or later
Flask
Other dependencies listed in requirements.txt
Installation
Install dependencies:
pip install -r
requirements.txt

Run the application:
python app.py
Usage
Open a web browser and go to http://127.0.0.1:5000.

Log in using the default admin credentials:
Username: admin
Password: password

Navigate through the home page to set rules, display lists, and check packets.
File Structure


project/
│
├── Firewall/
│ ├── init.py
│ ├── strategy_factory.py
│ ├── ip_filter.py
│ └── settings.py
│
├── templates/
│ ├── index.html
│ ├── home.html
│ ├── set_rules.html
│ ├── display_lists.html
│ └── check_packet.html
│
├── static/
│ └── style.css
│
├── app.py
└── Documentation.txt
