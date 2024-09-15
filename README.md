Yapping - Realtime Chatting Application

Yapping is a modern real-time chat application built with cutting-edge technologies to provide a seamless and fast communication experience. Whether it's for one-on-one chats or group discussions, Yapping ensures that your messages are delivered in real time with low latency, offering a sleek and intuitive user interface.
🚀 Features

    Realtime Messaging: Send and receive messages instantly using WebSockets.
    Typing Indicators: See when someone is typing a message.
    Read Receipts: Know when your messages have been read.
    Group Chats: Create or join group chats for collaborative conversations.
    User Presence: Check who's online or offline in real time.
    Rich Media Support: Share images, videos, and links within the chat.
    Custom Notifications: Get notified when you receive new messages.
    Emoji Reactions: React to messages with emojis for fun and expressive communication.

🛠️ Tech Stack

    Frontend: Next.js (React, TypeScript)
    Styling: Tailwind CSS
    Backend: Node.js with Next.js API Routes
    Database: Redis for in-memory storage and real-time data handling
    Real-time Communication: Pusher for WebSocket-based real-time messaging
    Authentication: NextAuth.js for secure authentication and session management

🎨 UI/UX Design

Yapping offers a sleek and minimalist UI design, making it easy for users to navigate and use the app. Its responsive design ensures that users have a smooth experience on both mobile and desktop devices.
📚 Getting Started

Follow these steps to set up Yapping locally:
Prerequisites

    Node.js (v16 or higher)
    Redis server
    Pusher account for WebSocket integration
    NextAuth.js setup for authentication

Installation

    Clone the repository:

    bash

git clone https://github.com/your-username/yapping.git

Navigate to the project directory:

bash

cd yapping

Install dependencies:

bash

npm install

Set up environment variables:

Create a .env.local file in the root directory and add the following:

env

NEXT_PUBLIC_PUSHER_KEY=your_pusher_key
REDIS_URL=your_redis_url
NEXTAUTH_URL=your_nextauth_url
NEXTAUTH_SECRET=your_nextauth_secret

Start the development server:

bash

    npm run dev

    The application will be available at http://localhost:3000.

Production

To deploy Yapping in a production environment, follow the instructions provided by your hosting service. Make sure to set your environment variables accordingly.
🧑‍💻 Development

To contribute to Yapping or customize it for your needs, follow these development steps:

    Fork the repository and create a new branch:

    bash

    git checkout -b feature/my-feature

    Make your changes and test them thoroughly.

    Commit and push your changes to your branch.

    Create a pull request, and we’ll review it!

Running Tests

Yapping uses Jest for unit and integration testing. Run the following command to execute tests:

bash

npm run test

🚀 Deployment

Yapping can be deployed to any platform supporting Node.js applications. Some options include:

    Vercel (for seamless Next.js deployments)
    Railway.app
    Heroku

Ensure your environment variables are correctly set in your deployment platform.
🛡️ Security

Security is a top priority in Yapping. Authentication is securely handled using NextAuth.js, and all real-time messages are transmitted over secure WebSocket connections using Pusher.

If you discover any security-related issues, please notify us at security@yapping.com.
📄 License

Yapping is open-source and available under the MIT License. See the LICENSE file for more information.
✨ Contributors

We welcome contributions! Please check the Contributing Guide for more details on how to get involved.