# Basic Git Workflow

This section explains the most common Git workflow used for small projects, especially with college students studying CS & IT.

## Step 1: Create a Repository
Create a new repository on GitHub using the green "New repository" button.

## Step 2: Clone the Repository
(This means creating a local copy of the repository on your own machine)
Copy the repository URL and run the following command in your terminal:

```bash
git clone https://github.com/username/repository-name.git
```

## Step 3: Make Changes
Open the git project folder that was created on your machine (located in "git" directory)
Using any text editor, add a file and create some simple changes.

## Step 4: Stage and Commit Your Changes:
After making local changes, you need to inform Git about which changes you'd like to "commit" to the online repository.

```bash
git add .
git commit -m "Describe your changes" (briefly describe the changes you made here)
```

## Step 5: Push Your Changes to the Online Repository:
This is the final step. You need to actually send or "push" the changes you made and committed to the online repository.
```bash
git push
```

<-- [Back to Home](README.md)  
--> [Common Mistakes](common-mistakes.md)

