# Live Code Sync

The **Live Code Sync** project is a web application designed for real-time code collaboration among multiple users. It allows participants to edit code simultaneously with instant synchronization.

## Features

- **Real-Time Collaboration**: Multiple users can edit code simultaneously with immediate updates.
- **Syntax Highlighting**: Supports various programming languages for better readability.
- **User Authentication**: Secure login system for session integrity.
- **Session Management**: Create and join coding sessions using unique identifiers.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js with Express.js
- **WebSockets**: Enables real-time bidirectional communication.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Shivamkumar1352/live-code-sync.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd live-code-sync
   ```
3. **Install Dependencies**:
   ```bash
   npm install
   ```
4. **Run the Application**:
   ```bash
   node server.js
   ```
5. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000` to start collaborating.

## Usage

- **Creating a Session**: Generate a unique session ID upon accessing the app.
- **Joining a Session**: Share the session ID with collaborators to join the same workspace.
- **Collaborative Editing**: Edit code in real-time, with changes synced instantly.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request with improvements.

## License

This project is licensed under the **MIT License**.

---
*Note: Ensure that you have Node.js installed before setting up the project.*
