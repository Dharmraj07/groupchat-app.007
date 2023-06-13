# GroupChat-App

The "GroupChat-App" repository is a production-ready application for group chat functionality. It provides a robust and scalable solution for facilitating real-time communication among users in a group setting. The application is designed to handle high traffic loads and maintain a seamless user experience.

## Key Features

- **Real-time Messaging**: Users can send and receive messages in real-time within group chats.
- **Group Management**: Users can create groups, join existing groups, and manage their group memberships.
- **User Authentication**: Secure user authentication and authorization mechanisms ensure that only authorized users can access and participate in group chats.
- **Message Archiving**: Messages are archived for future reference or retrieval, allowing users to access chat history.
- **Notifications**: Users receive notifications for new messages and group activities to stay updated.
- **Multimedia Support**: The app supports sharing images, files, and other multimedia content within group chats.
- **Robust Error Handling**: The application includes robust error handling and graceful degradation to handle unexpected scenarios and provide a smooth user experience.

## Tech Stack

- **Backend**: Node.js, Express.js, Sequelize (ORM)
- **Database**: MySQL
- **Authentication**: bcryptjs, jsonwebtoken
- **File Upload**: multer
- **Cross-Origin Resource Sharing (CORS)**: cors
- **Task Scheduling**: node-cron
- **Real-time Communication**: socket.io

## Dependencies

The "server" package.json file includes the following dependencies:

