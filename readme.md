Your login name: altschoolmain i.e., home directory /home/altschoolmain. 
The home directory contains the following sub-directories: code, tests, personal, misc Unless otherwise specified, 
you are running commands from the home directory.

Create user with the following:
- sudo useradd -d /home/altschoolmain -s /bin/bash altschoolmain
- id altschoolmain
- cat /etc/passwd | grep altschoolmain
- sudo passwd altschoolmain
- sudo usermod -aG sudo altschoolmain
- sudo cat /etc/group | grep sudo
- sudo su - altschoolmain

![Task a](image.png)

a. Change directory to the tests directory using absolute path name

![Task a](image-1.png)

b. Change directory to the tests directory using relative path name

![Task b](image-2.png)

c. Use echo command to create a file named fileA with text content ‘Hello A’ in the misc directory

![Task c](image-3.png)

d. Create an empty file named fileB in the misc directory

![Task d](image-4.png)

e. Copy contents of fileA into fileC

![Task e](image-5.png)

f. Move contents of fileB into fileD 

![Task f](image-6.png)

g. Create a tar archive called misc.tar for the contents of misc directory 

![Task g](image-7.png)

h. Compress the tar archive to create a misc.tar.gz file

![Task h](image-8.png)

i. Create a user and force the user to change his/her password upon login

![Task i](image-9.png)

j. Lock a users password

![Task j](image-10.png)

k. Create a user with no login shell

![Task k](image-11.png)

l. Disable password based authentication for ssh

![Task l](image-14.png)

m. Disable root login

![Task m](image-13.png)