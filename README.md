#  RealTime Whiteboard Sharing App

A real-time whiteboard built with **React**, **Socket.IO**, and **Node.js**.  
Users can **share a room** and **view** the presenter's live drawing updates.

----------

## ✨ Features

-   Presenter can draw and share in real-time
    
-   Viewers instantly see the drawing updates
    
-   Color picker to change drawing color
    
-   Undo/Redo actions
    
-   Clear the canvas
    
-   Room-based connection (join using Room ID)
    
-   Copy and share Room IDs easily
    
-   Fast updates using **WebSockets**
    

----------


## Built With

-   **Frontend**
    
    -   React
        
    -   TailwindCSS
        
    -   Socket.IO-client
        
    -   React-Toastify
        
-   **Backend**
    
    -   Node.js
        
    -   Express.js
        
    -   Socket.IO
        

----------

## ⚙️ Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/priyanshu0511/realtime-whiteboard.git
cd realtime-whiteboard

```

### 2. Setup Backend

```bash
cd server
npm install
npm start

```

> Server runs on `http://localhost:5000`

### 3. Setup Frontend

```bash
cd client
npm install
npm run dev

```

> Client runs on `http://localhost:5173`

----------


## 💡 Future Improvements

-   Allow multiple users to collaborate
    
-   Add touch support for mobile devices
    
-   Save canvas snapshots as images
    
-   Password-protected private rooms
    

----------

## Author

Made with ❤️ by **Priyanshu**

-   GitHub: [@Valtriac42](https://github.com/Valtriac42/)
    
-   LinkedIn: [Priyanshu Sharma](https://x.com/Priyanshu42v)
    

----------