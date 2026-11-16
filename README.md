# 1. What is this app?
A classic Ping Pong game built with C++ and SFML.

# 2. Prerequisites & Installing SFML
Before running the game, make sure you have **SFML** installed on your system:

* **On Linux (Ubuntu/Debian):** Install directly via terminal:
  ```bash
  sudo apt-get update && sudo apt-get install libsfml-dev
  ```
  *(Watch step-by-step video guide: [How to install SFML on Linux](https://youtube.com))*

* **On Windows:** Download the SDK from the [Official SFML Download Page](https://sfml-dev.org) and link it to your compiler.
  *(Watch step-by-step video guide: [How to Setup SFML on Windows](https://youtube.com))*

# 3. How to Use It
1. Open your Terminal (Linux) or CMD (Windows) and navigate to the project directory:
```bash
cd your_file_path
```

2. Compile the C++ code with SFML libraries linked:
```bash
g++ main.cpp -o ping_pong -lsfml-graphics -lsfml-window -lsfml-system
```

3. Run the game:
* **On Linux:**
```bash
./ping_pong
```
* **On Windows (CMD):**
```cmd
ping_pong.exe
```

# 4. Version
`1.0.1`
