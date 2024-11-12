# Django Chat Application

A real-time chat application built with Django and jQuery. This app allows users to create chat rooms and send messages in real time within these rooms.

## Features

- **Create and join chat rooms**: Users can create or join chat rooms by entering a room name and username.
- **Real-time messaging**: Messages are updated in real time using AJAX polling every second. Also added Auto-scroll Chat Display feature.
- **Responsive UI**: The application is styled to work well on various devices.
- **Django-powered backend**: Using Django to handle room and message management.
  
## Tech Stack

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript (jQuery)
- **Database**: SQLite (default in Django)

## Screenshots

### Main Page
![Main Page](main.jpg)

### Chat Room
![Chat Room](room.jpg)

## Installation

### Prerequisites

- Python 3.6+
- pip (Python package installer)
- Django 3.0+

### Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/django-chat-app.git
   cd django-chat-app
2. Create a virtual environment:
   ```bash
   python -m venv env
3. Activate the virtual environment:
   - on window:
     ```bash
      .\env\Scripts\activate
   - On macOS/Linux:
     ```bash
      source env/bin/activate
4. Install the required packages:
   ```bash
     pip install -r requirements.txt
5. Start the development server:
   ```bash
   python manage.py runserver
6. Open your browser and go to http://127.0.0.1:8000/

## Usage
 - Enter a room name and username on the landing page and click "Enter Room".
 - If the room does not exist, it will be created automatically.
 - Inside the chat room, type your message in the input field and click "Send" to chat in real time.
   
## Contributing
If you want to contribute to this project, please fork the repository and create a new branch for your **feature** or **bug fix**. Then, submit a pull request for review.

## License
This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
 - Django community for providing robust frameworks and resources.
 - jQuery for simplifying AJAX requests
 - DOpen-source communities for continuous support and contributions.

## Contact
For any inquiries, feel free to reach out to me:
- Email: pratikshasingh923@gmail.com

