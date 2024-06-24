[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277525&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
<br>
Go to your preferred browser,and type vs code download on the search engine.<br>
Navigate to the downloads page and select the download suitable for the operating system used by your personal computer or laptop and in this case,Windows 11.<br>
Also, ensure that your hardware is able to accomodate the vs code software in terms of ram,storage of the computer and its processor in terms of functionality.
<br>
One can also add extensions that they would use in coding in terms of a specific language; for instance in python, one can use a python debugger,pylance and so forth. You can also have Git connected to your vs code to allow easier pushing of code to your github environment.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
<br>
You can click on the file on the top left corner of an open tab on vs code and ensure you have your autosave ticked to ensure code is being saved automatically,therefore no loss of code.<br>
You can download extensions for formatting(JavaScript),debugging(Python Debugger) and having autocompletion as well.<br>
You can download Prettier when writing codes that need to be run on a web browser, this ensures even if you make any changes to your code, the browser will autorefresh and will have your up-to-date code structure.
<br>
Have version control whereby theres visualisation and tracking of code eg. Git and a debugger for your favourite browser to display the written code

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
<br>
The Activity Bar is the vertical bar on the far left side of the window.<br>
Manages files and folders within your workspace.<br>
Performs search operations within the working space.<br>
Integrates with version control systems (e.g., Git).<br>
Manages extensions, allowing you to browse, install, and configure them.
<br>
Side Bar is to the immediate right of the Activity Bar.<br>
Shows the file and folder structure of the workspace.<br>
Configures and controls debugging sessions.<br>
Lists installed extensions and recommendations.
<br>
Editor Group is where the actual file editing takes place.<br>
Allows you to open and edit files. Supports multiple editor tabs for multitasking<br>
Status Bar is the horizontal bar at the bottom of the window.<br>
Shows the current Git branch and status of the repository.<br>
Displays errors, warnings, and other notifications.
<br>

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
<br>
Command Palette is a feature that provides quick access to a wide range of commands and settings. it can be access through view > command pallette or shortcut (ctrl + Shift + P)<br>
Examples;<br>
Open of file and folder; click on file > New file or file > New folder <br>
Installations of extensions; Extensions > Install extensions <br>
Source control;Git: Commit to commit staged changes, Git: Push to push changes to the remote repository, Git: Checkout to to switch to another branch.
<br>
Debugging; Debug: Start Debugging to launch the debugger.
<br>

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
<br>
Extensions are used to enable additional languages, themes, debuggers, commands and improve your workflow.
Users can find,install extensions on the activity bar by clicking the extensions icon and searching for desired extensions. Extensions can be managed by clicking the downloaded extensions and ensuring they are up to date or updating them if need be.
<br>
Essential extensions include;<br>
HTML Boilerplate, HTML Snippets, CSS IntelliSense<br>
Prettier for formatting<br>
GitLens, GitHub Pull Requests and Issues, Live Share for collaoration and version control.<br>

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
<br>
Integrated terminal is access by clicking on ... > terminal > new terminal. It is a powerful feature that allows you to run command-line tasks from within the editor itself. 
<br>
Its advantages compared to an external terminal are;<br>
It can significantly enhance your workflow by eliminating the need to switch between VS Code and a separate terminal application<br>
Quick access, multiple terminals, and efficient task management therefore enhancing productivity<br>
Easy to manage multiple terminal sessions within the same interface. <br>
User can run and debug your applications while interacting with the terminal, making it easier to diagnose and fix issues.<br>
Unified environment and shared settings.
<br>

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
<br>
Creating and opening of files is done b clicking the top horizontal tab where you see file > new file , file > open folder.<br>
as for management of the files and folders one can right click on the active file on the side bar and rename,copy,delete amongst many other commands<br>
As for navigating between different files and directories efficiently, you can click on the file on the top left corner of the window, the open recent > and you'll be able to see all the directories you have interacted with recently as for the files , once your in the required directory you can interact with the files on the side bar of  the window.
<br>
You can also use the keyboard shortcut (Ctrl and + ) to zoom in and (ctrl  and -) to zoom out
<br>

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
<br>
To find and customize settings, it can be done through file > preferences > settings 
<br>
To change theme using the settings user interface, Ctrl + ' can be used to select the desired theme.<br>
to change using the command palette, ctrl + shift + p , type preferences: color theme, select and choose your desired theme.<br>
To change font size using the settings user interface, Ctrl + ' can be used to select the desired font size by typing font size, and adjusting editor: font size to the desired one.<br>
To change keybindings using the keybindings user interface, go to file > preferences > keyboard shortcuts ,Find the command you want to rebind, click on the pencil icon next to it, press the new key combination, and press Enter<br>

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
<br>
Install the extensions depending on the language used; eg for python-python, for C++ - C/C++<br>
this can be done by accessing the activity bar and clicking on the extensions icon to access the various extensions needed to download.
Debugging features available;<br>
Inspect variables in the variables section of the Debug view.<br>
Hover over variables in the editor to see their current values.<br>
View program output and interact with your program in the integrated terminal.<br>

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
<br>
Integration of Git with vs code can be done by;<br> 
Ensure Git is installed on your machine.<br>
Initialize a Git repository in your project using the Source Control view or Command Palette.<br>
Stage your changes and commit them with a descriptive message.<br>
Create a new repository on GitHub.<br>
Add the remote repository to your local Git configuration and push your changes.<br>


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

