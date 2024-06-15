[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15278886&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

There are basic prerequisites needed to install visual studio code on windows 11 oparational system:
 -- windows 11 operating system
 --internet connection
 --Git(for version control)
 --Administrator priviledges

 Steps:
 -- in your favourite browser navigate to <https://code.visualstudio.com/>
 --choose the windows version ![alt text](<Screenshot (4).png>)
 --click and download will start
 --open the downloaded file and accept the license terms
 --choose the installation location, e.g C:\Users\ElishaMafararikwa
 --install for user
 --after  installing launch and start coding

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   After installing VS Code you can do some configurations and settings to suit your working environment and preferences, e.g
   --create virtual envoronments that allows you to package different projects
   --change theme to your preference
   --edit settings like autosave,tab size, indent size, word wrap, intellicence etc.
   --explore keyboard shoprtcuts
   --set up the terminal to your preference
   --enable extensions like ESLint, prettier, Live Server,debugger, Gitlens etc
   -- install language extensions for your programming language

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

![alt text](<Screenshot (1)-3.png>)

Activity bar -- displays icons for activities -explorer, search, source control, debug, extentions.
   Open a window by clicking an icon.

Side bar --this bar shows the contents of the selected activity, eg  file tree, search results source control changes, debug console, extension settings

Editor group --coding area. where the cpode is displayed.

Status bar --this bar displays  information on the current file or project you are working on.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

      The command palette is a tool in vscode that allows you to get features and commands faster, by simply typing the keywords in the command pallette.
      --Command palette can be accessed by pressing CTRL+Shift+P (windows)
       or navigate on View- command palette.

   Common tasks that can  be perfomed by the command palette include -- new file,  git commands, debug commands, settings, extensions, terminal commands, tasks, new folder, replace, python, search, clear, extensions, explorer,

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

 --  Extensions are very important in  VSCode because they foster and enhance functionality in of vscode. tyey also allow developers to customise their coding experience.

 --Users can find extensions by by clicking the extension icon in the side bar and type  keywords of the extension, this will release a variety of extensions avialabe from which users can choose.

 --Install the extension you want by clicking the install button next to the  extension. this will download nand install the extension.

 --Managing extensions   Users can manage extension by  clicking on the extension. This will open a window in the editor group with the name of the extension. under it is the disable and uninstall buttons aswell as the settings icon .

--Examples of essential extensions are -- debugger, REST Client,Path Itellisense, Live Server, GitLens, Prettier, ESLint, bracket pair colorizer, docker,auto rename tag,

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   To open integrated terminal  --  go to view- choose terminal, thos will open a new terminal. OR
   -- click the terminal icon ( three dots in the side bar). then choose New Terminal. this will also create a new termial.

NOTE - terminal is created at the bottom of the vscode window displaying the command prompt

  To use  the integrated termial just type the commands and press enter.

 -- advantages of using integrated terminal over external terminal:
     -Convenience --easily accessible within vscode.
     -Context awareness -- it is aware of your current projects, making navigation easier.
     -Better intergration -- it is integrated with vscode enhancing functionality of features like auto command completion, code snippet insrtion, debugging and testing integration
     -Multi-terminal support -- this allows you to open more than one terminal, enabling multi tasking on projects
     -Features  -- terminal splitting, zooming, copy and paste
     -Perfomance -- optimized for high perfomance and responsive
     -Streamlined Workflow -- allows you to perfom terminal tasks without leaving you coding environment.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   - creating a file -- open vscode- click explorer- right click explorer panel- select new file- type file name and extension eg "index.html"- press enter.
   - opening a file --open vs code- click explorer icon- navigate the folder containing the file yo want- click on the file to open it in the editor.
   -managing files -- press Ctrl+S to save a file.
                   -- right click the file in the explorer panel and select 'delete' to delete it.
                   --drag and drop the file to a new lacation in the explorer panel tomove it.
                   --right click in the file, copy, right click and paste where you want to paste it.
                   -- click the file name the explorer panel- click rename icon- enter a new name
   - users can navigate through different files and directories in variuos ways eg  --keyboard shortcuts (Ctrl+Tab, Ctrl+ PageUp, etc), explorer panel, breadcrumbs(use the breadcrumps atb the top of the editor to  to navigate through the file path.), navigation history, customization, directory navigation, search, recent files etc.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   --Finding and customizing settings VSCode
     Settings - click view- command palette - preferences OR
              - Click setttings icon(gear icon at the left corner botton of the window) follow prompt.

--Change theme - click on the gear icon in lower left coner - settings- mtype theme and  set according to your preferences. OR
    --Click on extensions - type theme - install and set

-- Change font size -  click the gear icon -settings - type font size- in editor  type the font size to your pleasure.

 --Keybindings    -- Click the gear icon --click keyboard shortcuts-- click the pencil icon and modify--press enter

--
9. Debugging in VS Code:

- Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Steps to start debugging:
   --Set uo the project -create new folder for your project and create new file for your program
   --Write your code in the file
   --install neccessaryextensions by navigating to the extension panel , search and and install appropriate debugger
   --adjust settings as neccessary e.g lanch .jason
   --click the run button to start the debugger
   --use the debugger panel to step through code, inspect variables, etc
   --use the debugger to identify and fix issues
   --make changes to your code and start the debugger as neccessary.

   Key debugging features avialable in  VSCode:
  -integrated debugger--VSCode has built in debugger that supports debugging for a varietyb of languages.
  - Breakpoints --they pause exacution at nspecific lines of code allowing you to inspect variables
   -Step through Code-- line by line and stepping into functions support.
   -Data Inspection --inspect variables while debugging,view call stacks and explore data in Variables pane.
   -Debugger extensions- enhance functionality by adding a variety of appropriate extensions avialable on marketplace
   -Error handling -- catch and debug errors
   -Logponts -- set log points to output messegges to the console without stopping execution
   -Run and debug Configuration --configure launch settings, specifying parameterssuch as environment variables and many more.
   -Debug  console --evaluate expressions and valuables in the debug console

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

   -Launch VS Code
   -Open the folder or workspace of your project in vscode
   -Click on the source control icon,
   -Initialise git repository
   -configure git (firtst time)
    - in the source control panel stage changes by clicking the "+" button next to the files,
    -enter commit messege in the text box at the top of source control view
    - commit
    -create a repository in github
    - In VSCode type Git: Add Remote - choose github and aunthenticate
    -Click the three dots in the source control panel and from the drop down menu click push
    - VScode will prompt you to  select the branch you want to pushand the remote repository you want to push to
    -Choose your branch and confirm
    -Once completed changes will be visible in github.

-
  -

 Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July
