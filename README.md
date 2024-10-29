# 🏏 Fantasy Cricket Game

## Overview
The Fantasy Cricket Game is an online platform where users can create a virtual team of real cricket players. Players earn points based on their performance in actual matches, and the goal is to accumulate the highest score to win tournaments and achieve the top rank among participants. 🏆

## Features
- 👥 Create and manage a virtual cricket team.
- 📈 Earn points based on real-life performances of selected players.
- 🖥️ User-friendly graphical interface designed with PyQt5.
- 📊 Database integration using SQL or Excel sheets for player data management.
- 💯 Dynamic team score calculation based on player performance.

## Technology Stack
1. **Programming Language:** Python 🐍
   - Basic knowledge of loops, functions, and connections.
2. **GUI Framework:** PyQt5
   - Installation required.
   - Use of Qt Designer for GUI development (icons, layout management, etc.). 🎨
3. **Database Management:**
   - SQL or Excel Sheet for managing player data. 🗄️

## Database Design
1. **Player Database:**
   - Create a database containing player details.
   - Plan the required tables and populate them with player data.

2. **Tables and Structure:**
   - **Player Table:**
     - Columns: `player_id`, `name`, `team`, `role`, `points`, etc.
     - Data Types: Integer, String, Float, etc.
   - Additional tables as needed for game statistics and user data.

## Application Flow
- **UI Elements:**
  - 🔄 Populate the left list widget from the database based on the selected category radio button.
  - ➕ Add players from the players' list to the selected players' list.
  - ➖ Remove players from the selected players' list back to the players' list.
  - ❗ Show error messages if selection criteria are violated.
  - 📊 Calculate the total score of the selected team.

- **User Interface:**
  - Ensure symmetrical placement of UI widgets for a balanced layout. ⚖️

## Code Structure
- **Naming Convention:**
  - Use meaningful variable and function names for clarity. ✍️
- **Modularity:**
  - Functions should perform a single task to avoid code repetition and enhance maintainability. 🔄
- **Error Handling:**
  - Implement error handling wherever necessary to improve robustness. 🛠️

## Getting Started
### Prerequisites
- Python 3.x 🐍
- PyQt5 library (install using pip)
- Database software (SQLite, MySQL, or Excel for data storage) 💾

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Diksha0416/Fantasy_Cricket.git
   cd Fantasy_Cricket
   ```
2. Install the required packages:
   ```bash
   pip install PyQt5
   ```
3. Set up the database as described in the Database Design section. 📋

### Running the Application
To run the application, execute the following command:
```bash
python main.py
```
🚀

## Contribution
🤝 Contributions are welcome! Feel free to submit a pull request or open an issue for improvements.

## Acknowledgments
- [PyQt5 Documentation](https://www.riverbankcomputing.com/static/Docs/PyQt5/) 📚
- [SQLite Documentation](https://www.sqlite.org/docs.html) 📖
```
