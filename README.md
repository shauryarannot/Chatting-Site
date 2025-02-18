# Real-Time Chatting Application

## Overview
This is a real-time chatting application built using React.js, Mail.js, and other modern web technologies. It enables users to send and receive messages instantly, ensuring a seamless communication experience.

## Features
- Real-time messaging
- User authentication
- Email notifications via Mail.js
- Responsive UI for mobile and desktop
- Secure data transmission
- Typing indicators
- Message read receipts
- Group chat functionality
- User profile management

## Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js
- **Database:** MongoDB
- **Real-time Communication:** WebSockets (Socket.io)
- **Email Service:** Mail.js
- **Authentication:** JWT (JSON Web Token)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/chat-app.git
   cd chat-app
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Set up environment variables in a `.env` file:
   ```env
   REACT_APP_API_URL=your_backend_url
   MAILJS_PUBLIC_KEY=your_mailjs_key
   JWT_SECRET=your_secret_key
   ```

4. Start the development server:
   ```sh
   npm start
   ```

## Usage
1. Sign up or log in.
2. Create or join chat rooms.
3. Start messaging in real time.
4. Enable email notifications for new messages.

## Deployment
To deploy the application:
```sh
npm run build
```
Then host the `build/` directory on a static site provider like Vercel, Netlify, or Firebase Hosting.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-xyz`).
3. Commit your changes.
4. Push the branch and create a pull request.

## License
This project is licensed under the MIT License.

