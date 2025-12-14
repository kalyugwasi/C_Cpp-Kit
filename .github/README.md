# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" alt="Star" width="40" height="40" />C/C++ Kit

A complete C/C++ development kit with everything you need to get started with C/C++ programming, including graphics support and pre-configured VS Code tasks.
<br><br>
<p align="center">

  <!-- License -->
  <a href="https://www.apache.org/licenses/LICENSE-2.0" title="Apache 2.0 License">
    <img src="https://img.shields.io/badge/License-Apache_2.0-0e86d4?style=for-the-badge&logo=apache" alt="License: Apache 2.0">
  </a>

  <!-- Version -->
  <a href="https://github.com/kalyugwasi/Cpp-Kit/releases/latest" title="Latest Version">
    <img src="https://img.shields.io/github/v/release/kalyugwasi/Cpp-Kit?style=for-the-badge&logo=github" alt="Latest Release">
  </a>

  <!-- Downloads -->
  <a href="https://github.com/kalyugwasi/Cpp-Kit/releases" title="Total Downloads">
    <img src="https://img.shields.io/github/downloads/kalyugwasi/Cpp-Kit/total?style=for-the-badge&logo=windows" alt="Total Downloads">
  </a>

  <!-- Visitors -->
  <img src="https://api.visitorbadge.io/api/visitors?path=kalyugwasi/Cpp-Kit&countColor=%23f47373&style=for-the-badge" alt="Visitor Count">

  <br><br>

  <!-- DOWNLOAD BUTTON WITH GLOW EFFECT -->
  <a href="https://github.com/kalyugwasi/Cpp-Kit/releases/latest" title="Download Now">
    <img src="https://img.shields.io/badge/⬇️%20Download%20Now!-ff4757?style=for-the-badge&logo=github&logoColor=white" alt="Download Button">
  </a>

</p>


## 📍 Installation Paths

```
Compiler:           C:\mingw64
Examples:           %USERPROFILE%\Documents\Kalyug C++ Student Kit\Examples
VSCode Templates:   {app}\vscode-templates
```

> **Important:** After installation, open a new terminal or restart your PC to update PATH environment variables.

<br><br>
## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="40" height="40" /> Quick Start with VS Code

### First-Time Setup (For Graphics)

1. Download Latest release from top of the page (or [click here](https://github.com/kalyugwasi/Cpp-Kit/releases/latest))

![Release Install](./assets/release_install.gif)

2. Install the `.exe` File
3. Open **VS Code**
4. Go to **File → Open Folder**
5. Select:
   - 📂 `Documents`
   - 📂 `Kalyug C++ Student Kit`
6. Click **Select Folder**
7. If prompted, click:  
   → **Yes, I trust the authors**
8. Open: `Examples/circle.cpp`
9. Install: **C/C++ Extensions Pack**  
   *(VS Code will suggest automatically, or use this [link](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)*  
10. Press **Ctrl + Shift + D** → Select **Run Graphics C++**

<img src="./assets/debug.gif" alt="debug.gif" width="300" height="700">

11. Press **Ctrl + Shift + B** → Built
12. Press **F5** (or **Fn + F5**) → Run

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Party%20Popper.png" alt="Party" width="25" height="25" /> You’re ready to build graphics programs! <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Party%20Popper.png" alt="Party" width="25" height="25" />

<br><br>
## 🛠️ Building Your Code

### Using VS Code Tasks

| Task | Shortcut |
|------|----------|
| Show all build tasks | `Ctrl + Shift + B` |
| Show debug configuration | `Ctrl + Shift + D` |

**Available Tasks**
- **Build Normal C++** → Standard console apps
- **Build Graphics C++** → Programs using `graphics.h`

**Output Location:** `.bin\your_program.exe`

<br><br>
## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Glowing%20Star.png" alt="Star" width="30" height="30" /> Features

- ✅ MinGW-w64 C++ Compiler (64-bit)
- ✅ `graphics.h` + `winbgim.h` (WinBGIm library)
- ✅ `libbgi.a` Graphics Link Library
- ✅ Example Programs (Stars.cpp + Circle.cpp + rectangle.cpp)
- ✅ Pre-configured Build tasks for VS Code

<br><br>
## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Fire.png" alt="Fire" width="25" height="25" /> What's Included

| Component | Description |
|-----------|-------------|
| **Compiler** | MinGW-w64 GCC 15.2.0 (64-bit) |
| **Graphics Library** | WinBGIm for easy graphics programming |
| **Examples** | Sample C++ programs with graphics |
| **VS Code Setup** | Ready-to-use build tasks |


<br><br>
## Command Line

#### Standard C++ Program
```bash
g++ file.cpp -o a.exe
```

#### Graphics Program
```bash
g++ file.cpp -o a.exe -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
```
<br><br>
## 📚 Example Programs

| Program | Type | Description |
|---------|------|-------------|
| `stars.cpp` | Basic | First basic program |
| `circle.cpp` | Graphics | Draws a circle using graphics.h |
| `rectangle.cpp` | Graphics | Draws a rectangle using graphics.h |

<br><br>
## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Bug.png" alt="Bug" width="35" height="35" /> Troubleshooting

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

### File Compilation error

**Cause:** 
```
Expected:      %USERPROFILE%\Documents\Kalyug C++ Student Kit\Examples
Acutal:        %USERPROFILE%\onedrive\Documents\Kalyug C++ Student Kit\Examples 
```

**Solution:** Change the location of the file "Kalyug C++ Student Kit" to expected location
<br><br>
## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Handshake.png" alt="Handshake" width="35" height="35" /> Contributing

This project is free to share and improve. We welcome:
- Bug reports
- Feature suggestions
- Code improvements
- Documentation enhancements
- Sponsorship
<br><br>
## 🎯 Getting Help

If you encounter issues:

1. Check the **Troubleshooting** section above
2. Review the example programs
3. Verify your installation paths
4. Ensure all PATH variables are properly set
5. Contact me at <kumarhimanshu2609@gmail.com>

#

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Red%20Heart.png" alt="Love and Passion" width="25" height="25" />

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="title" content="C/C++ Setup with Graphics.h & VS Code">
<meta name="description" content="Free comprehensive C/C++ Development Kit featuring MinGW-w64 GCC 15.2.0 compiler, WinBGIm graphics library (graphics.h), pre-configured VS Code tasks, and example programs. Perfect for students, beginners, and educators. Zero configuration required - download and start coding in minutes!">
<meta name="keywords" content="C++ development kit, C++ compiler, MinGW-w64, GCC compiler, graphics.h, WinBGIm, winbgim.h, libbgi, Visual Studio Code C++, VS Code C++ setup, C++ graphics programming, beginner C++, learn C++, C++ tutorial, C++ IDE, C++ examples, C++ for students, Windows C++ compiler, C++ programming tutorial, free C++ compiler, C++ development environment, C++ graphics library, C++ starter kit, C++ installation guide, computer graphics C++, BGI graphics, Turbo C++ alternative, modern C++ setup, C++ education, programming for beginners">
<meta name="author" content="Himanshu Kumar">
<meta name="creator" content="Himanshu Kumar">
<meta name="publisher" content="Kalyug C++ Student Kit">
<meta name="copyright" content="© 2024 C/C++ Development Kit - Apache 2.0 License">
<meta name="license" content="Apache License 2.0">
<meta name="distribution" content="global">
<meta name="rating" content="general">
<meta name="target" content="students, educators, beginners, programmers, developers">
<meta name="classification" content="Software Development, Programming Tools, Education">
<!-- Detailed Description for Search Engines -->
<meta name="abstract" content="Complete C/C++ development environment with MinGW-w64 compiler, graphics programming support, and Visual Studio Code integration. Includes WinBGIm library for graphics.h functionality, example programs, and ready-to-use build configurations.">
<meta name="summary" content="All-in-one C/C++ programming kit with compiler, graphics library, IDE setup, and tutorials. Free, open-source, and beginner-friendly.">
<meta name="subject" content="C++ Programming, Software Development, Computer Graphics, Educational Tools">
<meta name="topic" content="C++ Development, Programming Education, Graphics Programming, IDE Configuration">
<!-- Open Graph / Facebook Meta Tags -->
<meta property="og:type" content="website">
<meta property="og:site_name" content="C/C++ Development Kit">
<meta property="og:title" content="C/C++ Development Kit - Complete Programming Setup with MinGW-w64 & Graphics Support">
<meta property="og:description" content="Everything you need for C/C++ programming: MinGW-w64 GCC 15.2.0 compiler, WinBGIm graphics library (graphics.h), VS Code tasks, example programs, and comprehensive documentation. Zero configuration - start coding immediately!">
<meta property="og:url" content="https://github.com/kalyugwasi/Cpp-Kit">
<meta property="og:locale" content="en_US">
<meta property="og:image" content="https://raw.githubusercontent.com/kalyugwasi/Cpp-Kit/main/assets/preview.png">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta property="og:image:alt" content="C/C++ Development Kit Preview - Compiler, Graphics Library, and VS Code Integration">
<!-- Twitter Card Meta Tags -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@kalyugwasi">
<meta name="twitter:creator" content="@kalyugwasi">
<meta name="twitter:title" content="C/C++ Development Kit - Complete Programming Setup">
<meta name="twitter:description" content="Free C/C++ programming kit with MinGW-w64 compiler, graphics.h support, VS Code integration, and example programs. Perfect for beginners and students!">
<meta name="twitter:image" content="https://raw.githubusercontent.com/kalyugwasi/Cpp-Kit/main/assets/preview.png">
<meta name="twitter:image:alt" content="C/C++ Development Kit - All-in-one programming solution">
<!-- GitHub Specific Meta Tags -->
<meta name="github:repository" content="kalyugwasi/Cpp-Kit">
<meta name="github:language" content="C++">
<meta name="github:topics" content="cpp, mingw, graphics, winbgim, vscode, compiler, education, beginner-friendly">
<!-- Search Engine Directives -->
<meta name="robots" content="index, follow, max-snippet:-1, max-image-preview:large, max-video-preview:-1">
<meta name="googlebot" content="index, follow, max-snippet:-1, max-image-preview:large, max-video-preview:-1">
<meta name="bingbot" content="index, follow, max-snippet:-1, max-image-preview:large, max-video-preview:-1">
<!-- Geographic & Language Meta Tags -->
<meta name="language" content="English">
<meta name="geo.region" content="WORLDWIDE">
<meta name="geo.placename" content="Global">
<meta name="content-language" content="en">
<!-- Refresh & Revisit Instructions -->
<meta name="revisit-after" content="7 days">
<meta http-equiv="refresh" content="604800">
<!-- Content Classification -->
<meta name="category" content="Software Development, Programming, Computer Science, Education, Tools">
<meta name="coverage" content="Worldwide">
<meta name="distribution" content="Global">
<meta name="audience" content="Students, Educators, Beginners, Programmers, Computer Science Students, Software Developers">
<!-- Software/Application Specific Meta Tags -->
<meta name="application-name" content="C/C++ Development Kit">
<meta name="software.version" content="Latest">
<meta name="software.developer" content="Himanshu Kumar">
<meta name="software.language" content="C++, C">
<meta name="software.platform" content="Windows">
<meta name="software.requirements" content="Windows 7/8/10/11, Visual Studio Code (Optional)">
<!-- Educational Context -->
<meta name="education.level" content="Beginner, Intermediate, Student">
<meta name="education.subject" content="Computer Science, Programming, Software Development">
<meta name="education.curriculum" content="C++ Programming, Computer Graphics, Software Engineering">
<!-- Technical Specifications -->
<meta name="tech.compiler" content="MinGW-w64 GCC 15.2.0">
<meta name="tech.graphics" content="WinBGIm, graphics.h, libbgi">
<meta name="tech.ide" content="Visual Studio Code">
<meta name="tech.platform" content="Windows 64-bit">
