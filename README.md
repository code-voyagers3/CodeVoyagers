# CodeVoyagers

# Table of Contents

1. [To contribute to this project you should](#to-contribute-to-this-project-you-should)
2. [Assignment](./Assignment/)
3. [Schedule](./Schedule/)
4. [Workflow Guide - Complete](./Guides/Workflow%20Long/)
4. [Workflow Guide - Dayli](./Guides/Workflow%20Short/)
5. [Groups](./Groups/)

<a name="to-contribute-to-this-project-you-should"></a>
## To contibute to this project you should:

### clone the code:

 - Open your browser and go to https://github.com/ellertsmari/CodeVoyagers (if you are not there already)
 - Click the green button where it says <> Code and copy the line that appears there
 - Open a terminal in your computer and navigate to a folder where you want to have your project.
    - Don't make a new folder for the project because Git will do that for you in the next step 
 - Type in `git clone [the text you just copied]`. Make sure to replace the "[the text you just copied]" with the text you copied in the second step here above
 - Now you should have a new folder named codeVoyagers. Open that folder in VSCode or any other IDE of your choice
 - Congratulations you now have the code from our repository open on your computer and you are ready to edit the code yourself!

 ### edit the code and commit your changes

  - Before you start editing the code make a new branch by typing `git checkout -b [the name of your branch]`. Make sure to replace the "[the name of your branch]" with the name that you want to choose for your branch (it can be anything but a good idea is to have it something that descripes what you are going to be doing)
  - Now if you type in `git status` you should be able to see that you are on your new branch
  - When you have made the changes that you want to make you can write the followint in your terminal (sometimes called the holy trinity of Git):
     - `git add .`
     - `git commit -m "[a description of what you did]"` Make sure to replace the squarebrackets and the text within it with an actual description of what you did
     - `git push origin [NameOfBranch]` be sure to replace the "[NameOfBranch]" wit the name of your branch. If you don't remember it you can always write `git status` to see it again
 - Now open https://github.com/ellertsmari/CodeVoyagers in your browser and you should see a button where it offers you to make a pull request. Click that button
 - Make the pull request but don't merge the code yet
 - If you see a pull request that has not been merged, you can review it and then merge it. Make sure to write some comments there