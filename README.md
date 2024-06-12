
# LSO Reader Project

The LSO Reader Project involves a Raspberry Pi device that reads RFID tags and communicates with a server to process and store data in a MySQL database. The project also includes a React frontend and a React Native mobile application for users to interact with the data.

## Project Author

Grzegorz Listwan

## Project Description

This project consists of several components:
1. **Raspberry Pi Device**: Reads RFID tags and sends data to the server, then reacts based on the server's response.
2. **Server**: Receives data from the Raspberry Pi, processes it, saves it in a database, and responds to the Raspberry Pi and frontend application.
3. **Frontend Application**: Communicates with the server, processes the responses, and displays the data to the user.
4. **Mobile Application**: Initially for Android, later for iOS, communicates with the server, processes the responses, and displays the data to the user.

## Technologies

- **Raspberry Pi**: Python
- **Backend**: Express Node.js
- **Database**: MySQL
- **Frontend**: React
- **Mobile Application**: React Native
