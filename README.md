# smart-note-awarahim
This is a basic smart note taking application using Python. 
Dependencies (library used):
- PyQt5
- json

How to extract and package this application into executable file (.exe file):
1. Download the "my_memory_card2.py"
2. Create new folder in your desktop and put this file in the folder. Rename the folder to "memory_card".
3. Open the "memory_card" folder in VSCode.
4. Run the "my_memory_card2.py"script and check if the application works or not.
5. If working, then can continue packaging the file into executable file thru the following steps:
          a. Check if "pyinstaller" installed  in your computer by writing this command to the terminal: "pip list"
          b. If not installed, write this in the terminal: "pip install pyinstaller"
          c. then create the .exe file by writing this in the terminal: "pyinstaller --onefile my_memory_card2.py"
6. Check your memory_card folder if the "dist" folder exist.
7. Go inside the "dist" folder,
8. cut the "my_memory_card2.exe" file,
9. and paste it back into the "memory_card" folder.
10. Run the "my_memory_card2.exe" to see if your application works or not.

Reference: https://pyinstaller.org/en/stable/index.html


