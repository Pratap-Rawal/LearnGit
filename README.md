I am trying git and github in LINUX OS. This is the first file I (loaded) pushed to github.
The most challenging process to accomplish was copying the key created by ssh-keygen from the root directory. Serendipity is the keyword for how  I figured out just now to copy the key generated by ssh-keygen command and saved in root directory.
Many hits and trials finally a solution. I realize it took me 3 hours to figure this out.

to find where the generated key is and to copy it. First keep changing directory one level up until root. then do ls -al to check contents of this directory. cd to root directory command prompt will show tilde forward slash and hash. then again ls -al to check content, cd to .ssh and check content again . now the file with ,pub extension is the one we are looking for. Coppy the content of this file and paste it in the github.
