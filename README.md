# Stream-talk

Stream-talk is a real-time streaming chat application built using Django as the backend. It allows users to create and join live chat rooms, conduct audio and video conversations, share screens, record sessions, and more.

## Features

- Real-time audio and video communication
- Dynamic user account creation
- Broadcasting capabilities

## Getting Started

To get started with Stream-talk, follow the steps below:

### Prerequisites

Before you begin, make sure you have the following prerequisites installed on your machine:

- Python
- Django
- Git (for cloning the repository)

### Clone the Repository

1. Open your terminal or command prompt.

2. Use the following command to clone the Stream-talk repository to your local machine:

   ```
   git clone https://github.com/aviAZIM/Stream-talk.git
   ```
### Create a Virtual Environment

1. Navigate to the project directory:
    ```
   cd Stream-talk
    ```
2. Create a virtual environment:
    ```
    python -m venv venv
    ```
3. Activate the virtual environment:

    - On Windows:
      ```
      venv\Scripts\activate
      ```
    - On macOS and Linux:
      ```
      source venv/bin/activate
      ```

### Install Dependencies
  - With the virtual environment activated, use pip to install the project's dependencies:
    ```
    pip install -r requirements.txt
    ```
### Migrate the Database
  - Run the following command to apply migrations and set up the database:
    ```
    python manage.py migrate
    ```
### Start the Development Server
  - Start the Django development server:
    ```
    python manage.py runserver
    ```
### The application will be accessible in your web browser at http://localhost:8000.

### Create a Chat Room
 - To create a new chat room, follow these steps:
   - Create a new user or login to the application.
   - Enter a name for the chat room 
   - Click the "Create Room" button.
   
### Join a Chat Room
  - To join an existing chat room, follow these steps:
    - Log in to the application.
    - Enter the chat room ID.
    - Click the "Join Stream" button.

### Contributing
  If you would like to contribute to Stream-talk, please feel free to create a pull request. We appreciate any help we can get to make Stream-talk the best streaming chat application possible.

### Contact
  If you have any questions or feedback, please feel free to contact us at email@example.com.
