# ChatsApp in Django

This is a personal chat messaging app built using Django, which allows users to send and receive messages in real-time. It's a simple and user-friendly application for personal conversations.

## Live demo and Screenshots

You can see a live demo by clicking [HERE]()

## Features

- User registration and login
- Real-time chat functionality
- User profiles with avatars
- Old Message history
- User-friendly interface

## Prerequisites

Before you start, ensure you have met the following requirements:

- Python 3.x on your machine.
- Git installed on your machine.

## Technologies Used

- Django 4.2
- Django Channels (for real-time communication)
- HTML
- CSS (using Tailwind CSS)
- JavaScript

## Installation & Setup Locally

### 1. Clone the github repository.

```bash
git clone https://github.com/anuraagnagar/messaging-app.git
```

### 2. Change the project directory.

```bash
cd messaging-app
```

### 3. Create and activate a virtual environment.

Creating virtual environment:

```bash
python -m venv venv
```

Activate virtual environment:

On Windows

```bash
venv\Scripts\activate
```

On MacOS/Linux

```bash
source venv/bin/activate
```

### 4. Install the requirements package.

```bash
pip install -r requirements.txt
```

### 5. Apply database migrations.

```bash
python manage.py migrate
```

### 6. Create a Superuser for admin.

```bash
python manage.py createsuperuser
```

### 7. Run the development server.

```bash
python manage.py runserver
```

### 8. Access the application

To access this application open your web browser and navigate to http://127.0.0.1:8000.

## Contributing

Contributions are welcome! If you find a bug or want to add a new feature, please open an issue or submit a pull request. For more information checkout [CONTRIBUTING.md](https://github.com/anuraagnagar/messaging-app/blob/main/CONTRIBUTING.md)

## License

This project is licensed under the [MIT License](https://github.com/anuraagnagar/messaging-app/blob/main/LICENSE) see for details.

## Author

[Anurag Nagar](mailto:nagaranurag1999@gmail.com)
