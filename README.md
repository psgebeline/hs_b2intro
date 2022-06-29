# hs_b2intro

This is a github repository which will be used to store all of our code in an open source format. Very ha#ndy in situations where you want multiple people to be working on the same code! We could easily do this without github, but it provides more organization and is a very useful tool for you to learn if you are going into physics, mathematics, or software development. they all use github. there are plenty reasons why github is extremely handy but you dont have to worry about most of them for now.

This readme will give you a general idea of how to stay organized with github.

1. Copying files

Firstly, do everything in your respective directory to stay organized. If you are using Wil or I's code as a template, dont make your edits on the file in our directory -- simply execute this command in your own directory:

cp /path/example.ipynb .   #the 'cp' means copy, and . means here. so this command is "copy this file to where i am"

To find the path, simply navigate to the target file and then execute:

pwd

2. Making changes

When you make changes to a file in your directory, you must push those changes to git. Firstly, execute:

git status

this tells you what files have and have not been pushed to the repository. 

to add your edited file to the staging area, execute:

git add file

obviously, change "file" to whatever file you're trying to add. you can also execute:

git add *

to add everything in the directory you are currently in.

once they have been added, commit the change with a short message:

git commit -m "message"

this commits everything in the staging area to the repository and displays a message. an example is "fixing bug"

finally execute:

git push

you will be prompted for your github username and github password. in this case, the password is not your password to github, it is the key for your personal access token, which i will go over in person.

there you go! your changes are live and i can see them from my laptop in my bed.

