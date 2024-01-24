# Github: Issue handle on a daily basis

## Step 14: Drag issues to the "In-Progress" column (see detailed version here)
When you have decided what issue you want to work on you drag it to the "In-Progress" column.
## Step 15:  Create a branch locally
1. Make sure you are on the develop branch 
	
	`git checkout developer`

2. Pull from develop branch

	`git pull`

3. Make, and checkout your own branch named issue#nr (where nr is the number of the issue you are trying to resolve)
	
	`git branch -b issue#number`

## Step 16: Work on the issue
1. Move the issue to In progress in the project plan. 
2. Change and add code to the project until you have solved the issue.

## Step 17: Push your code to your new branch
1. Add all changed files

	`git add .`

2. Commit your changes with the issue number and a commit message:

	`git commit -m "issue#[number] - [description]"`

	Replace [number] and [description] with the issue number and description og the changes you made.

3. Push your changes

	`git push origin issue#[number]`

## Step 18: Create a pull request
Go to GitHub and create a pull request from your branch into the develop branch

## Keep in mind
Remember to check on pending pull requests regularly and give helpful code reviews for them. To get started with code reviews you can try to copy-paste the code from the pull request into chatGPT or Github Co-pilot and ask it to help you make a code review
