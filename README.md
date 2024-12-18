
# NES Emulator in C++ with SDL

This is a cross-platform **NES Emulator** written in **C++** using **SDL** for graphics, input, and audio. The project focuses on precise hardware emulation to recreate the classic NES gaming experience while maintaining clear and modular code design.

---

## **Features**

- **Hardware Emulation**:
   - Emulates the NES CPU (6502), PPU (Picture Processing Unit), and memory-mapped I/O for accurate gameplay.
- **Cross-Platform**:
   - Developed with **SDL**, ensuring compatibility across Windows, macOS, and Linux.
- **Simple and Functional Design**:
   - Modular structure for readability and maintainability.
- **Classic NES Games**:
   - Load and play ROMs of original NES games for a nostalgic retro gaming experience.

---

## **Getting Started**

### Prerequisites

- **C++ Compiler** (e.g., GCC, Clang, or MSVC)
- **SDL2 Library**:  
  Install SDL2 on your system:  
  - On Ubuntu/Debian:  
    ```bash
    sudo apt-get install libsdl2-dev
    ```
  - On macOS (Homebrew):  
    ```bash
    brew install sdl2
    ```
  - On Windows: Download the SDL2 development library from [libsdl.org](https://www.libsdl.org).

### Building the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/SpideR1sh1/nes-emulator.git
   cd nes-emulator
   ```

2. Compile the project:
   ```bash
   g++ -std=c++17 main.cpp -o nes_emulator -lSDL2
   ```

3. Run the emulator:
   ```bash
   ./nes_emulator
   ```

### Running ROMs

1. Place a valid NES ROM file (e.g., `game.nes`) in the project directory.
2. Run the emulator and specify the ROM file as an argument:
   ```bash
   ./nes_emulator game.nes
   ```

---

## **Technical Details**

- **CPU Emulation**:
   - Implements the **6502 processor** instruction set for NES games.
- **PPU (Graphics) Emulation**:
   - Simulates the NES **Picture Processing Unit** for accurate frame rendering.
- **Input Handling**:
   - Uses SDL to manage keyboard inputs for NES controllers.
- **Memory Management**:
   - Implements memory-mapped I/O for accurate game state emulation.

---

## **Screenshots**

*(Add screenshots here of games running on your emulator)*

---

## **Planned Features**

- Save states for game progress.  
- Rewind functionality for enhanced gameplay.  
- Improved performance optimization.  
- Audio emulation for full NES sound support.

---

## **Tech Stack**

- **Language**: C++  
- **Libraries**: SDL2  
- **Tools**: G++/Clang (Compiler), Make (Build System)

---

## **Contributing**

Contributions are welcome! Feel free to open issues or submit pull requests to improve the emulator or add new features.

---

## **License**

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## **Acknowledgments**

- Inspired by [OneLoneCoder's olcNES](https://github.com/OneLoneCoder/olcNES).  
- Thanks to the NESDev community for documentation and support.
