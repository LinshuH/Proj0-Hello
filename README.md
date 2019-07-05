# Proj0-Hello
Trivial project to exercise version control, turn-in, and other
mechanisms.
By seperating the main program (.py) files and the credential.ini, this can protect some information that is suppose to hide.

In the "hello/" subfolder, the credentials.ini is putted together with the program. However, by considering the sercurity purpose in future while building the web application (for example, the authentication for the database accessing), should be seperate with the main program.

## Specification:

- Author: Linshu

- Contact address: echooogo@outlook.com

- What the software does: The main exacutive file of this software is called hello.py. Based on the message in file: "credentials.ini", py file will print the corresponding information. 

## How to run:
clone the repo, then cd into the "hello/" folder.
in this folder, type:
```
python3 hello.py
```
to run the program

The program would print the information on after "message=" in the credentials.ini, by changing the content, the output would be different.
