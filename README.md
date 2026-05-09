# SyncBoard

A real-time collaborative whiteboard application built for seamless team brainstorming, drawing, and live interaction.

## Features

* Real-time collaboration using WebSockets
* Multi-user drawing synchronization
* Create and join rooms instantly
* Smooth canvas drawing experience
* Responsive UI for desktop and mobile
* Fast and lightweight architecture
* Live updates without page refresh

## Tech Stack

### Frontend

* Next.js
* React.js
* Tailwind CSS
* HTML5 Canvas API

### Backend

* Node.js
* Express.js
* Socket.IO

## Project Structure

```bash
syncboard/
├── client/
│   ├── components/
│   ├── pages/
│   ├── public/
│   └── styles/
│
├── server/
│   ├── index.js
│   ├── socket/
│   └── utils/
│
├── package.json
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/syncboard.git
cd syncboard
```

Install dependencies:

### Frontend

```bash
cd client
npm install
```

### Backend

```bash
cd server
npm install
```

## Running the Project

### Start Backend Server

```bash
cd server
npm run dev
```

Server runs on:

```bash
http://localhost:5000
```

### Start Frontend

```bash
cd client
npm run dev
```

Frontend runs on:

```bash
http://localhost:3000
```

## Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=5000
CLIENT_URL=http://localhost:3000
```

## How It Works

1. Users join a room.
2. Drawing events are emitted through Socket.IO.
3. The server broadcasts updates to all connected users.
4. Every client canvas updates in real-time.

## Future Improvements

* Authentication system
* Persistent whiteboard storage
* Undo and redo functionality
* Shape tools
* Image uploads
* Export whiteboard as PNG/PDF
* Voice and video collaboration

## Screenshots

Add screenshots or GIFs here.

```md
![App Screenshot](./public/demo.png)
```

## Deployment

You can deploy:

* Frontend on Vercel
* Backend on Render/Railway

## Scripts

### Frontend

```bash
npm run dev
npm run build
npm run start
```

### Backend

```bash
npm run dev
npm start
```

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a pull request

## License

This project is licensed under the MIT License.

---

Built with real-time technology and collaborative thinking.
