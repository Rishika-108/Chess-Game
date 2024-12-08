# Chess Game ♟️  

**Chess Game** is an interactive web application that brings the timeless game of chess to the digital realm. Built using powerful backend technologies, this app ensures smooth gameplay with robust game logic and real-time interactivity.

## 🌟 Features  

- **Play Chess Online:**  
  Enjoy classic chess with a clean, interactive interface for an engaging experience.  

- **Move Validation:**  
  Powered by the **Chess.js** library, ensuring all moves follow the rules of chess.  

- **Game Progress Storage:**  
  Save and revisit your gameplay using MongoDB, enabling detailed analysis of moves and strategies.  

- **Multiplayer Support:**  
  Play against other users in real-time through robust server-side functionality using Node.js and Express.js.  

- **User Authentication:**  
  Secure login system to manage user profiles and game history.  

- **Responsive Design:**  
  Fully optimized for desktops, tablets, and mobile devices.  

## 🛠️ Tech Stack  

- **Backend:** Node.js and Express.js for server-side logic.  
- **Frontend:** HTML, CSS, and JavaScript for a user-friendly interface.  
- **Database:** MongoDB for efficient data storage.  
- **Chess Logic:** Chess.js library to handle gameplay rules and validation.  

## 🚀 Getting Started  

### Prerequisites  

Ensure you have the following installed:  
- [Node.js](https://nodejs.org/)  
- [MongoDB](https://www.mongodb.com/)  

### Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/Rishika-108/Chess-Game.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd Chess-Game  
   ```  
3. Install dependencies:  
   ```bash  
   npm install  
   ```  
4. Start the MongoDB server locally or connect to a MongoDB Atlas instance.  

### Running the App  

1. Start the backend server:  
   ```bash  
   npm start  
   ```  
2. Open your browser and navigate to `http://localhost:3000` to start playing.  

## 📂 Project Structure  

```plaintext  
Chess-Game/  
├── public/           # Frontend static files  
├── src/  
│   ├── routes/       # Express routes  
│   ├── models/       # MongoDB schemas  
│   ├── utils/        # Utility functions  
│   └── app.js        # Main server file  
├── package.json  
└── README.md  
```  

## 🤝 Contributing  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a new branch: `git checkout -b feature-name`.  
3. Commit your changes: `git commit -m 'Add feature-name'`.  
4. Push to the branch: `git push origin feature-name`.  
5. Submit a pull request.  

## 📜 License  

This project is licensed under the [MIT License](LICENSE).
