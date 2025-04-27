🛶 Missionaries and Cannibals Game (Python Console Version)
Welcome to the classic Missionaries and Cannibals river-crossing puzzle — implemented in Python!
This simple yet engaging console game challenges you to move all missionaries and cannibals from the right side of the river to the left side without ever allowing the cannibals to outnumber the missionaries on either side.
________________________________________
🎯 Objective
•	Safely move all 3 missionaries and 3 cannibals from the right bank to the left bank.
•	You must follow the game rules carefully to avoid losing!
________________________________________
🧠 Game Rules
•	The boat can carry at most 2 people and at least 1 person per trip.
•	At no point should cannibals outnumber missionaries on either side of the river (unless there are no missionaries present on that side).
•	If missionaries are ever outnumbered, you lose.
•	Move everyone across successfully, and you win!
________________________________________
🎮 How to Play
1.	The game starts with 3 missionaries (🧎) and 3 cannibals (👹) on the right bank.
2.	You will be prompted to enter the number of missionaries (M) and number of cannibals (C) you want to move.
3.	The boat's position toggles between right and left after each valid move.
4.	The state of the riverbanks and the boat is displayed after every move.
5.	Follow the rules — strategize your moves wisely!
________________________________________
🛠️ Code Structure
•	Variables:
  o	MR, CR: Missionaries and Cannibals on the Right side.
  o	ML, CL: Missionaries and Cannibals on the Left side.
  o	boat_side: Keeps track of the boat's current position ('right' or 'left').
•	Game Loop:
  o	Continuously accepts input for number of missionaries and cannibals to move.
  o	Validates moves according to the game rules.
  o	Updates the riverbanks and boat position accordingly.
  o	Checks for winning or losing conditions after each move.
•	Visuals:
  o	Emojis used:
    	🧎 (\U0001f482) - Missionary
    	👹 (\U0001f479) - Cannibal
    	🌊 (\U0001f30a) - River
    	🚢 (\U0001f6A2) – Boat
________________________________________
📚 What I Learned
While working on this project, I learned:
•	How to structure a game loop using while True and manage game states.
•	Implementing input validation to ensure only legal moves are accepted.
•	How to track dynamic changes in the game variables after each move.
•	Handling game win and loss conditions effectively.
•	Basic use of Unicode characters and emojis to make console output visually engaging.
•	Clear thinking required to transform a real-world puzzle into code logic.
This project really helped me understand the importance of state management, input handling, and logical flow control in Python programs.

________________________________________

▶️ How to Run
1.	Make sure you have Python 3 installed.
2.	Copy or download the script (.py file).
3.	Open a terminal and navigate to the folder containing the script.
4.	Run the script using:
          python filename.py
5.	Enjoy the game!
________________________________________
📷 Sample Gameplay Screenshot
          🧎🧎🧎 👹👹👹 🌊🌊🌊🌊🌊 🚢  
          Enter number of Missionaries to move: 1
          Enter number of Cannibals to move: 1
          (valid move)
          🧎 👹👹👹 🚢 🌊🌊🌊🌊🌊 🧎🧎 👹
          ...
________________________________________

🚀 Future Improvements (Optional Ideas)
    •	Add a move counter.
    •	Provide hints or suggested strategies.
    •	Implement a GUI version using Pygame or Tkinter.
    •	Add undo/redo functionality for moves.
________________________________________
📄 License
This project is open-source and free to use 
________________________________________
❤️ Acknowledgements
Special thanks to the creators of the classic Missionaries and Cannibals puzzle that has fascinated people for generations!

