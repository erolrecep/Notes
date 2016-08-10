 - cp file_name_1.txt file_name_2.txt #copies first txt file content over to another txt file.
 - cp * folder_name/ #moves all files/folders to under folder_name/.
 - echo text/string #standart output - will show the text.string on the terminal that you entered
 - cat file_name.txt #show the content of the text/othertype file.
 - cat file_name_1 >> file_name_2 #adds content 1 over to content 2.
 - cat < file_name # "<" takes argument from right and inputs to left.
 -  | #takes left command to right side.
 - cat file_name | wc #| takes the stout of the command on the left, and pipes it as standard input to the command on the right.(command to command)
 - cat file_name | sort > sorted_file_name.txt #converts to sorted version of the content.
 - 


## Tools
 - [./jq](https://stedolan.github.io/jq/) - jq is a lightweight and filexible commandline JSON processor.
 - [sed](https://www.gnu.org/software/sed/manual/sed.html) - sed, a stream editor.
 - [List of gnu softwares](https://www.gnu.org/software/)
 - [Learning the shell](http://linuxcommand.org/lc3_learning_the_shell.php)
 - [HTML-XML-utils](https://www.w3.org/Tools/HTML-XML-utils/)
 - [lyxn - text web browser](http://lynx.browser.org/lynx_help/Lynx_users_guide.html)
 - [curl](https://curl.haxx.se/) - to transfer data.
 - [zip](http://www.info-zip.org/mans/zip.html)
 - [unzip](http://www.info-zip.org/mans/unzip.html)
 - 


## How to install
**lynx**
sudo mkdir /usr/local/usr
cd /usr/local/src
sudo curl -O http://invisible-island.net/datafiles/release/lynx-cur.zip
sudo unzip lynx-cur.zip
cd lynx2-8-9
sudo ./configure --with-ssl --mandir=/usr/share/man
sudo make
sudo make install


## Problems&Solvings

 - How to install guestadditions to Linux by manuel : http://askubuntu.com/questions/321589/unable-to-mount-the-cd-dvd-image-on-the-machine-sandbox
 - 


