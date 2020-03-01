# SSH-Commands
Basic SSH Commands That You Should Know About

|Description | Command|
|---|---|
|ls|List all files and directories.|
|ls -l|Displays the details of the files, such as size, modified date and time, the owner, and the permissions.|
|ls -a|Shows hidden files and directories.|
|cd [directory]|cd (Change Directory) is the command that we use to jump between directories.|
|cd home/TestDirectory/AnotherDirectory|You are now in the AnotherDirectory.|
|cd ../ | Go To Root Directory (E:)|
|cd ../.. | Go To Home Directory|
|mkdir [folder name]|mkdir (Make Directory) command to create a directory.|
|touch [file name]| Used to create a new file|
|rm [file name]|removes a chosen file|
|rm -r home/hostinger/myfolder|To delete a folder, you need to use the -r option to remove all the files and subfolders inside it|
|cat [file name]|display the content of a file.|
|cat info.txt info2.txt > mergedinfo.text|It also allows you to create a new file by merging multiple files.|
|pwd|pwd is a simple command that outputs the full path of your working directory.|
|cp [options] source [destination]|copy files and folders.|
|cp myfile.txt myfile2.txt|copy file
|cp /home/hostinger/myfile.txt /home/etc/|If you want to make a copy in a different folder, run the following command|
|-f | if you don’t have writing permission to the destination file, it’ll be deleted and the command will create a new file|
|-u | copy the source file if it is newer than the destination file.|
|-n | will not overwrite an existing file.|
|-a | archive the files.|
|-R | Unlike duplicating files, copying folders requires you to use the -R (recursive) option.|
|cp -R /home/hostinger/myfolder /home/etc/|Sample|
|mv [source] destination|mv command will move the file or folder instead of copying it.|
|grep 'line' info.txt|command would search for ‘line’ in a file named “info.txt”.|
|-i|If you want to ignore letter cases, use -i option.|
|vi [file name]/nano [file name]|Vi and Nano are two popular text editors that you can use in the command line.|
|history 20|the example will show the 20 most recently entered commands.|
|clear|Clear Console|