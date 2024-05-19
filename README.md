# AnonChat 😎
AnonChat is a secure chat app meant to have disposable conversations anonymously built using the `Python-flask framework`. This has secure features such as end-to-end encryption and once the chat-room session is disposed all the messages will be deleted and no message/session data is stored at the server end as there is no database connected to the application. This is not meant for default usage of a chat application but only to be used when privacy is a concern.

![WhatsApp Image 2024-05-19 at 04 45 01_43879863](https://github.com/IT21311536/Secure-Disposable-Chat-App/assets/99274141/c423b560-a4fc-49f3-b2a8-f3dad3f60186)

![image](https://github.com/IT21311536/Secure-Disposable-Chat-App/assets/99274141/1e83644c-a144-4e67-a776-ea5bae4c2108)

## Collaborators
This project is a culmination of effort put together by `IT21311536` & `IT21357480`.

## Features

- End-to-end encryption for secure communication
- Disposable chat sessions with message deletion upon session termination
- Anonymous chat functionality

## Requirements

Please make sure you have all the Python dependencies installed. They are listed in the `requirements.txt` file.

## Installation

1. Clone the repository:
`git clone https://github.com/IT21311536/Secure-Disposable-Chat-App.git`

2. Navigate to the project directory:
`cd Secure-Disposable-Chat-App`

3. Create and activate a virtual environment (optional but recommended):
`python3 -m venv venv`
`source venv/bin/activate`  # On Windows use `venv\Scripts\activate`

4. Install the required dependencies:
`pip install -r requirements.txt`

## Usage

Run the application:
1. `python main.py`
2. Open your web browser and go to http://127.0.0.1:5000 to access the chat application.

## Testing
To test the application, follow these steps:

1. Open multiple browser windows or tabs and navigate to `http://127.0.0.1:5000` in each.
2. Start a chat session in one window and join the same session in the other windows.
3. Send messages and verify that they are encrypted and decrypted appropriately.
4. Dispose of the chat session and confirm that all messages are deleted.
