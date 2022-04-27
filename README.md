# Running-A-Local-HTTP-Server
## Introduction
Some HTML files can be opened directly as a local file by simply double-clicking and opening it on the user's default browser. However, some cannot be opened directly due to many reasons, such as:

1. Featuring asynchronous requests due to security restrictions
2. Featuring server-side languages like Python that requires a special server
3. Including other files that may trigger a [CORS](https://developer.mozilla.org/en-US/docs/Glossary/CORS) error

This tutorial will illustrate three ways to locally host an HTTP server in order test and run the HTML file.
## How To Run A Local HTTP Server
### Visual Studio Code's Live Server Extension
Visual Studio Code is a popular code editor that offers many benefits and extensions. One of their most popular extension is [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). If you are already coding with Visual Studio Code, then this extension is a must-have.

**Step 1.** Download [Visual Studio Code](https://code.visualstudio.com/) and launch the program.
  - Try and get familiar with Visual Studio Code as most people uses this code editor!
    
**Step 2.** Open the Extensions tab on the left-hand menu bar. The icon should look like this:
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/704606226553634932/968935262967193600/Screen_Shot_2022-04-27_at_2.02.24_PM.png">
</p>

**Step 3.** Search up "Live Server" and install it.
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/704606226553634932/968935801222205490/Screen_Shot_2022-04-27_at_2.04.44_PM.png" width="300">
</p>

**Step 4.** Open the project directory containing your HTML file in Visual Studio Code (Ctrl+O or ⌘+O) by searching through your computer.

**Step 5.** Right-click the HTML file displayed in the Explorer tab or right-click inside the body of the HTML file, and there is an option that says "Open with Live Server". Click on it, and you can now run your HTML file in a locally live server!
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/704606226553634932/968939084460478525/Screen_Shot_2022-04-27_at_2.16.56_PM.png" width="400">
</p>

### Python's `http.server` Module
Python is a popular programming language that offers many built-in modules, such as `http.server`. This module allows your HTML file to be run in a local HTTP server. You will have to use the Command Prompt (Windows) or Terminal (macOS/Linux) to setup your local HTTP server via Python's `http.server`.

**Step 1.** Download the latest version of [Python](https://www.python.org/).
  - As of April 2022, Python3 is the latest Python.
  - For Windows user, make sure to check the "Add Python 3.xxx to PATH" checkbox on the first installer page.
  - To verify that Python is downloaded, run `python3 -V` in the Command Prompt (Windows) or Terminal (macOS/Linux).
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/704606226553634932/968945220366516234/Screen_Shot_2022-04-27_at_2.41.25_PM.png" width="400">
</p>

**Step 2.** Change directory into your project's directory that contains your HTML file and other dependent files by using the `cd` command.

**Step 3.** Enter the command `python3 -m http.server` to run your local HTTP server.

**Step 4.** The local HTTP server will run on port 8000 by default. In your preferred web browser, type in [http://localhost:8000](http://localhost:8000) (or just [localhost:8000](http://localhost:8000)) to access your server!
