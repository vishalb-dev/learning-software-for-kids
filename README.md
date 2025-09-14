
# 🎓 Interactive Learning Software for Kids

An engaging educational C program designed to help children learn fundamental concepts through interactive graphics, animations, and sound. This software combines learning with fun through colorful visual elements and audio feedback.

## 📋 Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Program Structure](#program-structure)
- [Educational Modules](#educational-modules)
- [Screenshots](#screenshots)
- [Technical Details](#technical-details)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## ✨ Features

### 🔤 **Alphabet Learning**
- Interactive alphabet recognition (A-Z)
- Visual representations for each letter
- Associated objects and images for better memory

### 🔢 **Number Learning & Counting**
- Numbers 1-100 with visual counting
- Multiple representation styles (dots, shapes, objects)

### 🧮 **Mathematical Operations**
- **Addition**: Visual step-by-step addition with counting aids
- **Subtraction**: Interactive subtraction with borrowing concepts
- **Multiplication**: Comprehensive multiplication with visual arrays
- **Multiplication Tables**: Complete tables for any number (1-99)

### 🎨 **Visual & Audio Features**
- Colorful graphics and animations
- Sound effects 
- Interactive user interface
- Multiple visual learning aids

## 🔧 Prerequisites

- **Turbo C++ Compiler** (Recommended version 3.0 or higher)
- **Windows DOS environment** or DOSBox emulator
- **BGI Graphics Library** (usually included with Turbo C++)
- **Sound card support** for audio features

## 📥 Installation

1. **Clone the repository:**
git clone https://github.com/yourusername/interactive-learning-software.git
cd interactive-learning-software

2. **Set up Turbo C++ environment:**
- Install Turbo C++ IDE
- Ensure BGI graphics library is in the correct path (`\TURBOC3\bgi`)

3. **Compile the program**

## 🚀 How to Run

1. **Using Turbo C++ IDE:**
- Open the `.c` file in Turbo C++
- Press `Ctrl+F9` to compile and run
- Or use `Alt+F9` to compile, then `Ctrl+F9` to run

2. **From Command Line:**
- learning_software.exe

3. **Using DOSBox (for modern systems):**
- Install DOSBox
- Mount the program directory
- Run the executable

## 📖 Program Structure

Main Menu Options:
<br>
├── 1. Learn Alphabets → Interactive A-Z learning
├── 2. Learn Counting → Numbers 1-100 with visuals
├── 3. Addition → Step-by-step addition problems
├── 4. Subtraction → Interactive subtraction with borrowing
├── 5. Multiplication → Visual multiplication methods
├── 6. Multiplication Tables → Complete tables for any number
└── 7. Exit → Program termination



## 📚 Educational Modules

### Alphabet Module
- **Input**: Any letter key (A-Z)
- **Output**: Visual representation with associated objects
- **Examples**: A for Apple, B for Ball, C for Car, etc.
- **Features**: Colorful graphics, sound feedback

### Counting Module
- **Range**: Numbers 1-100
- **Visual Aids**: Various shapes (circles, squares, triangles)
- **Learning Method**: Progressive counting with different representations

### Mathematics Modules
- **Addition**: Supports 1-digit and 2-digit numbers
- **Subtraction**: Includes borrowing concepts for 2-digit numbers
- **Multiplication**: Handles 1-digit × 1-digit up to 3-digit × 2-digit
- **Tables**: Generates multiplication tables for numbers 1-99

## 🖼️ Screenshots

*Note: Add screenshots of your program running here*


## 🔨 Technical Details

- **Language**: C (ANSI C compatible)
- **Graphics**: Borland Graphics Interface (BGI)
- **Compiler**: Turbo C++ 3.0+
- **Platform**: DOS/Windows 16-bit
- **Libraries Used**:
  - `stdio.h` - Standard I/O operations
  - `conio.h` - Console I/O (DOS-specific)
  - `graphics.h` - BGI graphics functions
  - `dos.h` - DOS-specific functions
  - `stdlib.h` - Standard library functions
  - `string.h` - String manipulation

### Key Functions
- `music()` - Sound generation
- `border()` - UI border creation
- `Alphabets()` - Alphabet learning module
- `Counting()` - Number counting module
- `Addition()` - Mathematical addition
- `Subtraction()` - Mathematical subtraction
- `Multiplication()` - Mathematical multiplication
- `Table()` - Multiplication tables

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/new-feature`
3. **Make your changes**
4. **Test thoroughly**
5. **Commit your changes**: `git commit -m "Add new feature"`
6. **Push to the branch**: `git push origin feature/new-feature`
7. **Open a Pull Request**

### Areas for Improvement
- [ ] Port to modern C++ with modern graphics libraries
- [ ] Add more educational modules (shapes, colors, etc.)
- [ ] Implement progress tracking
- [ ] Add difficulty levels
- [ ] Create configuration options
- [ ] Add more languages support

## 👥 Credits

- **Developer**: [Your Name]
- **Guided by**: MR. ASHOK BHARDWAJ
- **Educational Consultant**: [If applicable]

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Known Issues

- Requires DOS/16-bit environment to run
- Graphics path must be correctly configured
- Sound functionality depends on system sound card
- Limited to Turbo C++ compiler compatibility

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Contact: [your-email@example.com]

---

⭐ **Star this repository if you find it helpful!**

*Made with ❤️ for young learners everywhere*

