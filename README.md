# newRepo



First step in creating a repositiry is to go to github and create a new one. This can be done from the command line but I find it is just much easier to do it this way. Once this is done you can clone a copy of the Repo via the command  "git clone" + the url address of the desired repository. 

![Screenshot (92)](https://user-images.githubusercontent.com/61522963/125860411-5f7754bb-0ac5-4516-94f1-a8e5b100265f.png)

Once this has been completed, you can cd into newRepo and create a new file.


![Screenshot (93)](https://user-images.githubusercontent.com/61522963/125860602-6a20ec4d-d236-40eb-83a4-920a80d8bf08.png)

I compiled and ran HelloSquirrel just to double check that it worked.

Now that we've made a file it is not tim to commit or changes to the repository
You can also use "git status" to check which files in your repository have been changed or not

![Screenshot (96)](https://user-images.githubusercontent.com/61522963/125860754-25e6375d-1ce4-4cb2-a119-752332ded470.png)

First we want to add HelloSquirrel.java. note that we do not want to add class files, only source code. So HelloSquirrel.class can be ignored (If you have a gitignore file you can make it ignore class files)
Next we commit the changes and add a commit message. Since it is the first commit of this repository I wrote "Initial Commit"

Finally if we want to make changes to HelloSquirrel, we can open it up, change whatever we want, and then just make another commit.
