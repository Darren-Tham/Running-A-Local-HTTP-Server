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

**Step 4.** Open your HTML file or the directory containing your HTML file in Visual Studio Code (Ctrl+O or ⌘+O) by searching your computer. (The Explorer tab should have opened up with your HTML file being displayed)

**Step 5.** Right-click the HTML file displayed in the Explorer tab or right-click inside the body of the HTML file, and there is an option that says "Open with Live Server". Click on it, and you can now run your HTML file in a locally live server!
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/704606226553634932/968939084460478525/Screen_Shot_2022-04-27_at_2.16.56_PM.png" width="400">
</p>
