# Ping Pong

## 1. About the Project
A classic Ping Pong arcade game built with C++ and SFML.

## 2. Motivation & Features
* **Motivation:** Created as a coding challenge to practice 2D game physics, rendering, and event handling using C++ and SFML.
* **Key Features:**
  * **Smooth Gameplay:** Real-time paddle movement and ball collision physics.
  * **Lightweight & Fast:** Built directly with SFML graphics, window, and system modules.

## 3. Prerequisites & Installation
Before compiling and running the game, ensure you have **SFML** and a C++ compiler (`g++`) installed:

### Linux
* **Ubuntu / Debian / Mint:**
  ```bash
  sudo apt-get update && sudo apt-get install libsfml-dev g++
  ```
* **Fedora / RHEL / CentOS:**
  ```bash
  sudo dnf install SFML-devel gcc-c++
  ```
* **Arch Linux / Manjaro:**
  ```bash
  sudo pacman -S sfml gcc
  ```
* **openSUSE:**
  ```bash
  sudo zypper install sfml2-devel gcc-c++
  ```
* **Alpine Linux:**
  ```bash
  sudo apk add sfml-dev g++
  ```
* **Other Distributions:** Download the source or SDK from the [Official SFML Download Page](https://sfml-dev.org).

### Windows
Download the SDK from the [Official SFML Download Page](https://sfml-dev.org) and link it to your compiler (MinGW or MSVC).

## 4. Build & Run

### 1. Clone & Compile
Open your Terminal (Linux) or Command Prompt (Windows) and run:
```bash
git clone https://github.com
cd Pink-Pong
g++ main.cpp -o ping_pong -lsfml-graphics -lsfml-window -lsfml-system
```

### 2. Run the Game
* **On Linux:**
  ```bash
  ./ping_pong
  ```
* **On Windows (CMD):**
  ```cmd
  ping_pong.exe
  ```

## 5. Version
`1.0.1`
