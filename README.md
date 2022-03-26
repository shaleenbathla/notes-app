# Notes app in NodeJS
Notes app made using NodeJS
TUI only

This is a server-side application which can be used to create your personal notes from the terminal and save them in a json file.

The following 4 commands are available:
1. add --title="....." --body="....."    #to add a new note
Example: node app.js add --title="Shopping List" --body="Peas,Potato,Onion"
2. remove --title="....."                #to remove a note
Example: node app.js remove --title="Shopping List"
3. list                                  #to list all the notes
Example: node app.js list
4. read --title=" "                      #to read a note
Example: node app.js read --title="Shopping List"


Step1 : git clone https://github.com/shaleenbathla/notes-app.git

Step2 : Install node on your machine

Step3 : npm install

Step4 : node app.js <command> <sub-commands>
