# GuiPractice

## Description
A collection of Python files to practice making application windows

## Tricks
### How to make a program shortcut on a Windows computer
	1. Right-click on the source code file. 
	2. Select the option to Create shortcut
	3. Open the Properties of the shortcut
	4. In the Target box, add python.exe (without quotes) before the filename
		- For example, if the original target is 
		"C:\Users\Your\Documents\YourPythonProgram.py",
		change this to python.exe "C:\Users\Your\Documents\YourPythonProgram.py".
		- When you apply this change, Windows will add the full path to python.exe
		- The next time you view the shortcut properties, the target will look like
		"C:\Path\To\Python\Interpreter\python.exe" "C:\Users\Your\Documents\YourPythonProgram.py"
	5. Change the Run option to Minimized. This will minimize the command-prompt (console) window, leaving your
		Python program window at its normal size.
	6. When you double-click on the shortcut, you will see two items on the taskbar related to your program.
		- The visible item is your program.
		- The hidden item is the minimized command-prompt (console) window.
		- Task Manager shows two Python processes, 
