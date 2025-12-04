# Capstone-AI-Project
Beginner-friendly C# programming toolkit built for the Moringa AI &amp; Software Engineering curriculum. Includes setup instructions, sample code, debugging steps, and AI prompt journal.
# Prompt-Powered Kickstart: Beginner Toolkit for C#

This toolkit guides beginners through installing .NET, running a C# console app, and learning through AI prompting.
MyToolkit/
│
├─ Program.cs
├─ MyToolkit.csproj
├─ README.md   ← documentation
└─ .gitignore
## Title & Objective
- Prompt-Powered Kickstart: Beginner Toolkit for C# Programming Language  
- Objective: To help beginners install .NET and VS Code, scaffold a simple C# console app, run and debug it, and document the AI prompts used during learning.

## Quick Summary of the Technology
- **What C# is:** C# is a modern, object-oriented programming language developed by Microsoft. It's strongly typed, used for building desktop apps, web APIs (with ASP.NET), game development (Unity), and more.
- **Where it is used:** Web backends (ASP.NET Core), desktop apps (WPF/WinForms), cloud services, game development (Unity).
- **Real-world example:** Companies like Microsoft, StackOverflow, and many enterprise systems use C# and .NET for backend services and web APIs.

## System Requirements
- Windows 10/11
- Visual Studio Code
- .NET SDK (6/7/8 - LTS recommended)
- Git (for version control)
- Recommended VS Code extensions: C# (OmniSharp), C# Dev Kit

## Installation & Setup Instructions
1. Install .NET SDK: https://dotnet.microsoft.com/download
2. Install Visual Studio Code: https://code.visualstudio.com/
3. Install Git: https://git-scm.com/
4. Create project folder:
   ```powershell
   mkdir Moringa-CSharp-Project
   cd Moringa-CSharp-Project
   
Save `README.md`.

---

## 8) Add AI Prompt Journal entries (examples)
Add the prompts you used while building. Save them inside `README.md` (as above) or in a separate `prompts.md`. Examples:

- `How to install .NET SDK on Windows?`
- `dotnet new console vs dotnet new console -f net7.0` (if you need a specific TFM)
- `How to add launch.json for .NET console debugging in VS Code?`
🎯 a. Learning the Language
Explain C# to me like I’ve never coded before. Keep it simple and use everyday analogies, not technical jargon.

🚀 b. Debugging with Style
Why is my C# console app not printing output? Show me likely mistakes and fixes presented as a detective mystery.

🤖 c. Code + Storytelling
Turn my Hello World program into a funny story narrated by the computer itself, but keep the code valid and runnable.

🧠 d. Concept Clarity
Teach me what C# namespaces are using a real-world example, like organizing rooms in a house.

👩🏽‍💻 e. Self-Reflection Prompt
Help me reflect on today’s coding session with C#: what went well, what confused me, and how I can improve tomorrow.

🎨 f. Formatting Assistance
Rewrite my README with a modern developer tone, emojis, section icons, and GitHub-friendly formatting.

🔍 g. Error Fixer
I got this C# error: CS0103. Explain what it means, why it happens, and give me two ways to fix it.

🧪 h. Experiment Prompt
Give me three variations of a C# console output that display text in different styles (uppercase, colored, timed).

📚 i. Learning Roadmap
Create a 2-week beginner roadmap to learn C# and .NET, broken down by daily goals and mini-projects.

🧩 j. Code Optimization Fun
Rewrite my C# code to be cleaner and more efficient, but explain the changes like you are a helpful s

## 🧠 AI Prompt Gallery
Below are creative prompts used during development to assist learning, debugging, and understanding C# concepts:

- "Explain C# to me like I’ve never coded before…"
- "Teach me what namespaces are using a house analogy…"
- "Fix this CS0103 error and explain the root cause…"


---

## 9) Build an executable (optional)
To create a self-contained deployable:

```powershell
dotnet publish -c Release -r win-x64 --self-contained false -o ./publish

![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![Tech](https://img.shields.io/badge/Language-C%23-blue)
![Runtime](https://img.shields.io/badge/.NET-8.0-purple)
