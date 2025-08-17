# snake-game-c-progam
This project is a classic Snake Game implemented in the C programming language using a console interface. The game involves controlling a snake to eat food items randomly placed on the board. Each time the snake eats the food, it grows longer. The game ends when the snake collides with the wall or itself.

This project enhances understanding of:

2D arrays,

Basic game logic,

Collision detection,

Keyboard input handling (_getch()),

Use of loops and conditionals,

Procedural programming in C.
#🚀 How to Run This Project
1️⃣ Clone the Repository

Make sure you have Git installed.

git clone https://github.com/akshitasharma0716/snake-game-c-progam.git
cd snake-game-c-progam


👉 If you don’t have Git, click the green Code button on GitHub → Download ZIP → Extract it.

2️⃣ Install C Compiler

You need a C compiler (GCC) to run this project.

Windows: Install MinGW and add C:\MinGW\bin to PATH.

Linux / macOS: GCC is usually pre-installed. Check with:

gcc --version

3️⃣ Compile the Code

Go to the project folder and run:

Windows (CMD/PowerShell):

gcc snake.c -o snake.exe
snake.exe


Linux / macOS (Terminal):

gcc snake.c -o snake
./snake


(If your main file has a different name, replace snake.c with that filename.)

4️⃣ Run in VS Code (Optional but Easy)

Install VS Code.

Install extensions:

C/C++ (Microsoft)

Code Runner (optional).

Open the project folder in VS Code.

Open snake.c and press Ctrl + ` to open the terminal.

Run:

gcc snake.c -o snake
./snake   # Linux/Mac
snake.exe # Windows

✅ Example Gameplay

When you run the game, you’ll see:

###############
#             #
#    @        #
#             #
###############

Score: 0


@ = Snake head

* = Food

Arrow keys / WASD → Move snake

📌 Author

Developed by Akshita Sharma
