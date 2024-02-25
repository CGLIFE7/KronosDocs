<h1> Install Dependencies</h1>

![Alt Text](images/Enable.png){: style="height:75%;width:75%"}

<h3>What am I installing and why?</h3>

<br>

BQT - Allows for using QT gui within blender, this is used for the image search tool to display a custom image window.

qtpy - Required for BQT

Pyside6 - Required for BQT

BS4 - Used for downloading images for image search

Requests - Used for downloading images for image search

<h3>Windows only</h3>

<br>
pygetwindow - Used by image search for windows to determine wether the window needs to be minimized or not.

Plyer - Used by render without GUI to send a toast notification to your OS on render finish

<br>

<h3>Mac Only</h3>

<br>
pyobjc/iterm2 - Required for BQT

pync - notifications for render without gui

<br>
File path for installing dependencies is Kronos\addon\operator\prefs\install_dependencies.py, if you would like to confirm yourself.
