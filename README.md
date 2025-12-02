# Kalyug C++ Student Kit

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-1.0-blue.svg)](#)
[![Maintained by Himanshu](https://img.shields.io/badge/Maintained%20by-Himanshu-brightgreen.svg)](#)

A complete C++ development kit for students with everything you need to get started with C++ programming, including graphics support and pre-configured VS Code tasks.

## ✨ Features

- ✅ MinGW-w64 C++ Compiler (64-bit)
- ✅ `graphics.h` + `winbgim.h` (WinBGIm library)
- ✅ `libbgi.a` Graphics Link Library
- ✅ Example Programs (Hello World + Graphics)
- ✅ Pre-configured Build tasks for VS Code

## 📦 What's Included

| Component | Description |
|-----------|-------------|
| **Compiler** | MinGW-w64 GCC 15.2.0 (64-bit) |
| **Graphics Library** | WinBGIm for easy graphics programming |
| **Examples** | Sample C++ programs with graphics |
| **VS Code Setup** | Ready-to-use build tasks |

## 📍 Installation Paths

```
Compiler:           C:\mingw64
Examples:           %USERPROFILE%\Documents\Kalyug C++ Student Kit\Examples
VSCode Templates:   {app}\vscode-templates
```

> **Important:** After installation, open a new terminal or restart your PC to update PATH environment variables.

## 🚀 Quick Start with VS Code

### First-Time Setup (Super Easy!)

**The `.vscode` folder with all configuration files is already included!** No setup needed.

#### Step-by-Step:

1. **Open VS Code** on your computer

2. **Open the Project Folder**
   - Go to: `File` → `Open Folder`
   - Select the Cpp-Kit project folder
   - Click `Select Folder`

3. **Trust the Folder**
   - VS Code will ask "Do you trust the authors of the files in this folder?"
   - Click `Yes, I trust the authors` ✅

4. **Verify Configuration**
   - In VS Code's Explorer (left sidebar), you should see `.vscode` folder
   - This folder contains:
     - `tasks.json` - Build configuration
     - `launch.json` - Debug configuration
   - No need to edit these files!

5. **Ready to Code!** 🎉
   - Create your `.cpp` file in the project folder
   - Save it
   - Press `Ctrl + Shift + B` to build
   - Your executable will be in `.bin\` folder

> 💡 **Pro Tip:** All configuration is done for you. Just open the folder in VS Code and start coding!

## 🛠️ Building Your Code

> 🔥 **This is the most important section!** Follow these steps to compile and run your programs.

### Method 1: Using VS Code Tasks (Recommended) ⭐

**Step 1: Prepare Your Code**
- Create your C++ file (e.g., `program.cpp`) in your project folder
- Make sure your code is saved

**Step 2: Open Task Menu**
- Press `Ctrl + Shift + B` in VS Code to open the task palette

**Step 3: Choose Your Build Type**

#### For Programs WITHOUT Graphics
```
Select: Build Normal C++
```
This compiles standard C++ code using the basic g++ compiler.

#### For Programs WITH Graphics (using graphics.h)
```
Select: Build Graphics C++
```
This compiles with all necessary graphics libraries:
- `-lbgi` (BGI graphics library)
- `-lgdi32` (Windows GDI)
- `-lcomdlg32` (Common dialogs)
- `-luuid` (UUID)
- `-loleaut32` (OLE)
- `-lole32` (OLE)

**Step 4: Run Your Program**
- Navigate to `.bin\` folder in your project directory
- Double-click `your_program.exe` to run it
- Or open PowerShell/CMD and type: `.\.bin\your_program.exe`

**Step 5: View Output**
- Your executable appears in: `.bin\your_program.exe`
- All build output is shown in the VS Code terminal

---

### Method 2: Using Command Line (Advanced)

#### For Standard C++ Programs
```bash
g++ program.cpp -o program.exe
./program.exe
```

#### For Graphics Programs
```bash
g++ program.cpp -o program.exe -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
./program.exe
```

#### Compile with Custom Output Directory
```bash
g++ program.cpp -o .bin\program.exe -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
```

---

### Quick Reference Table

| Task | Steps | Time |
|------|-------|------|
| **Build Normal C++** | Press `Ctrl + Shift + B` → Select "Build Normal C++" | ~2-5 sec |
| **Build Graphics C++** | Press `Ctrl + Shift + B` → Select "Build Graphics C++" | ~2-5 sec |
| **Run Program** | Go to `.bin\` folder → Double-click `.exe` or run in terminal | Instant |
| **Check Errors** | Look at VS Code terminal output | Real-time |

## 📚 Example Programs

| Program | Type | Description |
|---------|------|-------------|
| `stars.cpp` | Basic | First basic program |
| `circle.cpp` | Graphics | Draws a circle using graphics.h |
| `rectangle.cpp` | Graphics | Draws a rectangle using graphics.h |

## 🐛 Troubleshooting

### Error: 'initgraph' or 'circle' undefined

**Cause:** Missing graphics library link flags

**Solution:** Use the "Build Graphics C++" task instead of the normal build task

### Error: g++ command not recognized

**Cause:** PATH environment variable not updated

**Solution:** 
- Restart your PC, OR
- Open a fresh terminal window (close and reopen your terminal)

### Graphics not displaying

**Cause:** Graphics.h requires specific Windows libraries

**Solution:** Ensure you're using the "Build Graphics C++" task which includes all necessary library links

## 💡 Tips & Tricks

- Always use "Build Graphics C++" task for programs that include `graphics.h`
- Keep your source files in the root folder for easy access
- Output executables appear in `.bin\` directory
- Use the examples as templates for your own programs

## 📖 About This Kit

This toolkit is designed to help students quickly start with C and C++ programming, with special focus on **Classic Computer Graphics** commonly taught in Indian colleges and universities.

### Philosophy

- 🎓 Educational focus
- 🔧 Easy setup and configuration
- 📚 Learning through examples
- 🎨 Graphics programming support

## 🤝 Contributing

This project is free to share and improve. We welcome:
- Bug reports
- Feature suggestions
- Code improvements
- Documentation enhancements

## 📄 License

This project is open source with no restrictions. Free to use, modify, and distribute.

## 🎯 Getting Help

If you encounter issues:

1. Check the **Troubleshooting** section above
2. Review the example programs
3. Verify your installation paths
4. Ensure all PATH variables are properly set

---

**Happy Coding!** 😎🔥

Made with ❤️ by Himanshu
