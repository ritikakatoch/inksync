
A Real-Time Collaborative Whiteboard Web App.
---
## Features
* Share canvas in real-time easily just by sharing a link.
* Chat with people in the room.
* Own file extension .ink Save the drawing files locally on your device.

## Installation

1. Clone the repository to your local machine.
    ```sh
    git clone https://github.com/ritikakatoch/InkSync.git
    ```
    
2. Install the required packages.
    ```sh
    cd InkSync
    npm install
    
    cd server
    npm install
    ```
    
3. Set up the environment variables:
   Create a .env file in the root directory
   ```sh
   NEXT_PUBLIC_SERVER_URL= # URL of the server (e.g. http://localhost:3000 in development mode)
   ```
   Create a .env file in the server directory
   ```sh
   PORT = "5000"
   ```
   

5. Start the development server.
    ```sh
    npm run dev
    ```
