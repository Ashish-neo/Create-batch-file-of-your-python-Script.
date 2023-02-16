# Create-bat-file-of-your-python-Script.

To create a batch file for your Python script, you can follow these steps:

Open a text editor such as Notepad.

Type the following line at the beginning of the file:
```
@echo off
```
This will prevent the command prompt from displaying commands as they are executed.

Type the following line to run your Python script:
```
python "path/to/your/script.py"
```
Replace "path/to/your/script.py" with the actual path to your Python script.

Then use Pause to keeping running 
```
Pause
```
Save the file with a .bat extension, for example "run_script.bat".

Your batch file is now ready to run. Double-click on the file to execute your Python script.
