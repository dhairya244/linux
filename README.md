# linux
 Save file at some location, example in Desktop folder.
 Now, go to terminal and enter command :
chmod +x internsct1
 This command will make above file executable.
 Now, you need to add the internsct1 file to the environment path in your bash script file
 To do this, do the following:
 Enter command :
 nano ~/.bashrc
 It will open bash script file in terminal
Scroll down and in the end enter this :
export PATH=$PATH:$HOME/Desktop
 And now in keyboard enter this :
 Ctrl+O , it will save the changes in nano
 Now, press the enter button to confirm filename.
And now, press Ctrl+X button in keyboard to exit from the bash/nano.
 Now, in terminal enter this command to apply changes in current shell session:

source ~/.bashrc
Now, process is completed and internsct1 command is created.
 Enter these commands to verify changes :
 internsct1 cpu getinfo
 internsct1 memory getinfo
 Everything should work
