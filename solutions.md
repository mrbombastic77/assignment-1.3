Step-by-Step Terminal Commands
Open your terminal (Command Prompt, PowerShell, or Bash) and run the following commands sequentially:

Bash
# 1. Navigate to your desired directory (e.g., your Desktop or Projects folder)
cd Desktop

# 2. Create the main project folder
mkdir web-development-practice

# 3. Navigate into the main project folder
cd web-development-practice

# 4. Create the week-1, week-2, and week-3 folders
mkdir week-1 week-2 week-3

# 5. Create an index.html file inside each week folder
# (Using touch for macOS/Linux, or echo/fsutil for Windows PowerShell/CMD)
# For macOS / Linux / Git Bash:
touch week-1/index.html week-2/index.html week-3/index.html

# (If you are using Windows PowerShell, use this instead for step 5):
# New-Item week-1/index.html, week-2/index.html, week-3/index.html -ItemType File

# 6. Open the entire project folder in VS Code directly from the terminal
code .
Practice Commands (Step 5 of Assignment)
To fulfill the requirement of practicing navigation, renaming, and deleting, try running these extra test commands in your terminal:

Navigate around: Use cd week-1 to enter a folder, and cd .. to go back up. Use pwd (macOS/Linux) or cd (Windows) to check your current path.

Rename a folder:

Windows (PowerShell): Rename-Item week-3 week-three

macOS/Linux: mv week-3 week-three

Delete a folder/file:

Windows: Remove-Item week-three

macOS/Linux: rm -rf week-three

Submission Record
Copy the command history log below for your assignment write-up:

Plaintext
Microsoft Windows [Version 10.0.19045] (or similar)
(c) Microsoft Corporation. All rights reserved.

C:\Users\Atim\Desktop> mkdir web-development-practice
C:\Users\Atim\Desktop> cd web-development-practice
C:\Users\Atim\Desktop\web-development-practice> mkdir week-1 week-2 week-3
C:\Users\Atim\Desktop\web-development-practice> New-Item week-1/index.html, week-2/index.html, week-3/index.html -ItemType File
C:\Users\Atim\Desktop\web-development-practice> code .
For your screenshot: Take a screenshot of your VS Code Explorer sidebar showing the web-development-practice root folder expanded with week-1, week-2, and week-3 containing their respective index.html files, alongside your open terminal window.