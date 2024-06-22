[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292094&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   - PREREQUISITES
      Windows 11 OS, 1 GB of RAM, 1.6 GHz CPU processor.
   
   -INSTALLATION
      Download the VS Code installer for Windows from a credible source e.g: Microsoft Store.
      Once downloaded, run the installer through the VSCodeUserSetup-{1.90.1}.exe.
      You can modify the installation path for ease of access.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

      The settings can be accessed manually through File>Preference>Settings or through the keyboard shortcut Ctrl+,.
   
      Settings that could be adjusted depending on user's preference include the theme, the auto save feature that prevents data loss, the location of the activity bar, key bindings by modifying the 'keybindings.json, the debug toolbar etc.

      Language specific extensions for syntax highlighting, these include Python, C/C++. Version control extensions; GitLens, GitHub Pull Requests and Issues for GitHub Integration.
      Docker to manage Docker containers and images directly from VS Code.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

      -Activity Bar
         This is located on the left side of the VS Code window though it can be modified as per user's need.

         Its main purposes is offering quick access to different views and functions within VS Code.

      -Side Bar
         This is located to the right of the Activity Bar

         Its main purpose is displaying context-specific content depending on the selected activity. For instance; when the Extensions icon is selected, the Side BAr shows the different extensions where you can navigate and manage them.
         It also shows the search results, source control status, explorer and debugging information.

      -Editor Group
         This is the central part of the VS Code interface where you write and edit your code.

         Its main purpose is it offers the platform where you open files to view and edit their contents.

      Status Bar
         This is located at the bottom of the VS Code window.

         Its main purpose is to provide information about the current state of the editor and the project. It also shows the notifications and errors and provides quick access to settings and tasks.       

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette is a powerful feature that provides quick access to a wide range of commands and functionalities and acts as a centralised hub for executing various tasks without needing to navigate through menus or remember complex keyboard shortcuts.
   
   To access it, one can use the Ctrl+Shift+P shortcut or clicking View on te menu bar and then select Command Palette.

   Common tasks that can be performed using the Command Palette include:
   Opening Files and Folders-
   Navigating to Symbols
   Running and Debugging Code
   Source Control
   Settings and Preferences
   Formatting and Linting
   Snippets and Shortcuts

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

      Extensions in Visual Studio Code (VS Code) play a crucial role in enhancing its functionality and customizing the development environment to suit specific needs. They allow users to add new features, languages, debuggers, and more, thereby transforming VS Code from a lightweight code editor into a powerful integrated development environment (IDE). Extensions can help in:
      Adding support for additional programming languages.
      Integrating with version control systems.
      Enhancing debugging capabilities.
      Providing advanced code editing features like linting, formatting, and snippets.
      Integrating with external tools and services.
    
      Finding Extensions. There are two ways of finding extensions on VS Code. By using the Extensions View on the Activity Bar and By Visiting the Visual Studio Code Marketplace in a web browser though I'll delve into the first option that I am conversant with.
    
    Finding  
  Click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X.
  Use the search bar at the top of the Extensions view to find extensions by name, category, or functionality.

   Installing
   In the Extensions view, find the extension you want to install.
   Click the Install button next to the extension name.
   The extension will be downloaded and installed automatically.

   Managing 
   Go to the Extensions view (Ctrl+Shift+X).
   The list of installed extensions will be shown under the Installed section.
   
   Enabling/Disabling Extensions:
   Right-click on an installed extension in the Extensions view.
   Choose Disable to turn off the extension without uninstalling it, or Enable to turn it back on.
   
   Updating Extensions:
   Extensions are updated automatically by default.
   If an update is available, you will see an update button next to the extension in the Extensions view.
   
   Uninstalling Extensions:
   Right-click on the installed extension in the Extensions view.
   Choose Uninstall to remove the extension from VS Code.

   Essential Extensions for Web Development

   JavaScript (ES6) code snippets: Provides JavaScript snippets for common ES6 syntax.
   HTML Snippets: Adds snippets for HTML code.
   ESLint: Integrates ESLint into VS Code to provide JavaScript linting.
   Prettier - Code Formatter: Automatically formats your code to ensure consistency.
   Stylelint: Lints CSS/SCSS/Less code to enforce consistent styling.
   Live Server: Launches a local development server with live reload feature for static and dynamic pages.
   Path Intellisense: Autocompletes file paths in the editor.
   GitLens: Enhances the built-in Git capabilities with features like blame annotations, code lens, and repository insights.
   GitHub Pull Requests and Issues: Allows you to manage GitHub pull requests and issues directly from VS Code.
   Debugger for Chrome: Allows you to debug JavaScript code in the Chrome browser directly from VS Code.
   Jest: Integrates the Jest testing framework, providing features for running and debugging tests.
   Docker: Provides tools to manage Docker containers, images, and compose files.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   There are several ways to open the Integrated Terminal
      Using Menu>View>Terminal
      Using Ctrl+`
      Using Ctrl+Shift+P then type 'Toggle Terminal
   
   Using the Integrated Terminal
      Opening Multiple Terminals
         Clicking the '+' icon in the terminal opens a new terminal instance
         Switching between multiple terminals can be done using Ctrl+Pagedown and Ctrl+Pageup
      Splitting Terminals
         Click the split terminal icon, next to the '+', to split the terminal into multiple panes
      Running Commands
         Type commands directly into the terminal just as you would in an external terminal.
      Customising the Terminal

   Advantages of using the Integrated Terminal over an External Terminal
      Convenience and workflow integration
      Enhanced productivity
      Better resource management
      Customisation and consistency
      Enhances featires- by extension integration

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

      Creating Files and Folders
Using the Explorer View:
    Open the Explorer view by clicking the Explorer icon in the Activity Bar or by pressing Ctrl+Shift+E.
   To create a new file:
   Right-click on the folder where you want to create the file.
   Select New File.
   Enter the file name and press Enter.
   To create a new folder:
   Right-click on the parent directory.
   Select New Folder.
   Enter the folder name and press Enter.
Using the Command Palette:
   Press Ctrl+Shift+P to open the Command Palette.
   Type File: New File and select it to create a new file.
   Type Explorer: New Folder and select it to create a new folder.
Using Keyboard Shortcuts:
   Press Ctrl+N to create a new untitled file.
   Save the new file by pressing Ctrl+S and specifying the directory and file name.
   Opening Files and Folders
Using the Explorer View:
   Click on the Explorer icon in the Activity Bar or press Ctrl+Shift+E.
   Click on any file or folder to open it in the editor.
Using the Command Palette:
   Press Ctrl+Shift+P to open the Command Palette.
   Type File: Open File or File: Open Folder and select the command.
   Choose the file or folder from the dialog box that appears.
Using Keyboard Shortcuts:
   Press Ctrl+O to open the Open File dialog box.
   Press Ctrl+K Ctrl+O to open the Open Folder dialog box.
Using Quick Open:
   Press Ctrl+P (or Cmd+P on Mac) to open the Quick Open dialog.
   Start typing the name of the file you want to open, and select it from the list.
Renaming Files and Folders:
   Right-click on the file or folder in the Explorer view.
   Select Rename.
   Enter the new name and press Enter.
Moving Files and Folders:
   Drag and drop the file or folder to the desired location within the Explorer view.
   Alternatively, cut (Ctrl+X) and paste (Ctrl+V) the file or folder to move it.
Deleting Files and Folders:
   Right-click on the file or folder in the Explorer view.
   Select Delete.
   Confirm the deletion if prompted.
      Navigating Between Different Files and Directories Efficiently
Quick Open:
   Press Ctrl+P (or Cmd+P on Mac) to quickly open any file by typing its name.
   This is one of the fastest ways to navigate between files.
Go to Definition and Go to Symbol:
   Press F12 to go to the definition of a symbol.
   Press Ctrl+Shift+O to open the Go to Symbol in File dialog and navigate to a symbol within the current file.
   Press Ctrl+T to open the Go to Symbol in Workspace dialog and navigate to a symbol across the entire workspace.
Navigate Back and Forward:
   Use Alt+Left Arrow to navigate back to the previous location.
   Use Alt+Right Arrow to navigate forward to the next location.
Explorer View:
   Use the file explorer to quickly switch between files and directories by clicking on them.
Open Recent:
   Press Ctrl+R to open the list of recently opened files and workspaces.
   This is useful for quickly accessing files you have worked on recently.
Breadcrumbs:
   Enable breadcrumbs by clicking the breadcrumb icon in the upper right corner of the editor or by selecting View > Show Breadcrumbs.
   Use the breadcrumbs to navigate to parent directories or symbols within the file.
Search:
   Press Ctrl+Shift+F to open the search pane.
   Use the search functionality to find files and symbols across your entire workspace.
Sidebar and Tabs:
   Use the sidebar (Explorer view) to organize and navigate your project structure.
   Use tabs to keep multiple files open and switch between them easily.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   Accessing Settings
Using the Menu:
   Go to File > Preferences > Settings.

Using the Command Palette:
   Press Ctrl+Shift+P to open the Command Palette.
T  ype Preferences: Open Settings and select it.
Using the Keyboard Shortcut:
   Press Ctrl+,
   Settings Editor
The Settings editor provides two views:
   User Settings: Applies settings globally for all projects.
   Workspace Settings: Applies settings only to the current workspace or project.
Customizing Settings with Examples
Changing the Theme
Using the Command Palette:
   Press Ctrl+Shift+P.
   Type Preferences: Color Theme and select it.
   Browse and select a theme from the list.
Using the Settings UI:
   Open the Settings editor.
   Search for theme in the search bar.
   Find the Color Theme dropdown and select the desired theme.
Manually Editing Settings JSON:
Open the settings JSON file by clicking the {} icon at the top right of the Settings editor.
Add or modify the following line in settings.json:"editor.fontSize": 18
   Changing the Font Size
Using the Settings UI:
   Open the Settings editor.
   Search for font size in the search bar.
Modify the Editor: Font Size setting to the desired size (e.g., 18).
Manually Editing Settings JSON:  
   Open the settings JSON file.
   Add or modify the following line in settings.json:
   json
Changing Keybindings
Using the Menu:
   Go to File > Preferences > Keyboard Shortcuts (on Windows).
Using the Command Palette:
   Press Ctrl+Shift+P.
   Type Preferences: Open Keyboard Shortcuts and select it.
Using the Keyboard Shortcuts:
In the Keyboard Shortcuts editor, search for the command you want to modify.
Click the pencil icon next to the command.
Press the new key combination you want to assign to the command.
Press Enter to save the new keybinding.
Manually Editing Keybindings JSON:
Open the Keyboard Shortcuts JSON file by clicking the {} icon at the top right of the Keyboard Shortcuts editor.
Add or modify keybindings in keybindings.json. For example, to change the keybinding for saving all files to Ctrl+Alt+S:
json

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Step 1: Install Necessary Extensions
   Ensure you have the appropriate language extension installed for your project. For example, for JavaScript/Node.js, install the Debugger for JavaScript extension; for Python, install the Python extension.
Step 2: Open or Create a Project
   Open VS Code.
   Open a folder that contains your project files (File > Open Folder or Ctrl+K, Ctrl+O).
Step 3: Write a Simple Program
   Create a file for your program, for example, app.js for a Node.js application.
   Add simple code
Step 4: Configure the Debugger
   Open the Debug View:
   Click on the Debug icon in the Activity Bar on the side of VS Code.

Alternatively, press Ctrl+Shift+D.
Create a Debug Configuration:
   Click on the gear icon to open the launch.json file.
   Select the environment for your program. For Node.js, choose Node.js. For Python, choose Python.
   A default launch.json configuration file will be created in a .vscode folder in your project.
Step 5: Set Breakpoints
   Open your app.js file.
   Click in the gutter to the left of the line numbers where you want to set breakpoints. A red dot will appear indicating the breakpoint.
Step 6: Start Debugging
   Run the Debugger:
   In the Debug view, ensure the configuration is selected (e.g., "Launch Program").
   Click the green play button or press F5 to start debugging.
   Debugging Controls:
   The debugging toolbar appears at the top with controls:
   Continue (F5): Resumes the program until the next breakpoint.
   Step Over (F10): Executes the next line of code but doesn't enter functions.
   Step Into (F11): Enters the next function call.
   Step Out (Shift+F11): Exits the current function.
   Restart: Restarts the debugging session.
   Stop: Stops the debugging session.

Key Debugging Features in VS Code
Breakpoints:
   Set breakpoints by clicking in the editor margin.
   Conditional breakpoints can be added by right-clicking on a breakpoint and adding conditions.
Watch Expressions:
   Add expressions to the Watch panel to monitor their values during execution.
   Access the Watch panel in the Debug view.
Call Stack:
   View the call stack in the Call Stack panel to understand the sequence of function calls.
   Helps in identifying where the code is currently paused and how it reached there.
Variables:
   Inspect variables in the Variables panel to see their current values.
   Expand objects and arrays to inspect nested values.
Debug Console:
   Use the Debug Console to evaluate expressions, execute code, and view output during debugging.
   Access the console from the Debug view or by pressing Ctrl+Shift+Y.
Exception Handling:
   Configure the debugger to break on exceptions.
   Customize handling for different types of exceptions (uncaught, caught).
Inline Values:
   View variable values inline within the editor during a debugging session.
Logpoints:
   Similar to breakpoints but logs a message to the console instead of stopping execution.
   Useful for logging variable values without modifying the code.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Open VS Code:
   Open the folder or workspace where you want to initialize the Git repository.
Initialize Git Repository:
   Open the Command Palette (Ctrl+Shift+P).
Type and select Git: Initialize Repository.
   Choose the directory where you want to create the repository.
Set Up Git Configurations:
   If this is the first time you're using Git on your machine, you may need to configure your name and email:

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Making Commits
Stage Changes:
   Make changes to your files in VS Code.
   Open the Source Control view by clicking on the Source Control icon in the Activity Bar on the side (or use Ctrl+Shift+G).
   You'll see your changed files listed under "Changes".
   Click the + button next to each file to stage them for commit.
Commit Changes:
Enter a commit message summarizing the changes you've made in the text box above the list of changed files.
Click the check mark icon (or use Ctrl+Enter) to commit your changes.
Pushing Changes to GitHub
Add Remote Repository (GitHub):
   Go to GitHub and create a new repository if you haven't already done so.
   Copy the HTTPS or SSH URL of your GitHub repository.
Add Remote in VS Code:
   In VS Code, open the Command Palette (Ctrl+Shift+P).
Type and select Git: Add Remote.
   Paste the URL of your GitHub repository.
Push Commits to GitHub:
   Open the Command Palette again.
   Type and select Git: Push.
   Choose the remote branch (usually origin for GitHub).
   Enter your GitHub credentials if prompted.
Verify Changes on GitHub
   Go to your GitHub repository in a web browser.
   You should see your committed changes reflected in the repository.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

