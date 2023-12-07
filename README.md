# Getting Started with Git and GitHub

## Create a New Feature Branch

The following is a step-by-step guide on how to create a new feature branch, stage, commit, and push changes using the built-in terminal and source control in Visual Studio Code:

1. **Open the Terminal in VS Code**
   - You can open the terminal in VS Code by clicking on `Terminal` in the menu bar and then selecting `New Terminal`.

2. **Create a New Feature Branch**
   - In the terminal, check out to the branch from which you want to create your new feature branch (usually the `main` branch). You can do this with the command: `git checkout main`.
   - Now, create and switch to the new feature branch using the command: `git checkout -b your-branch-name`.

3. **Make Changes to Your Files**
   - Make the necessary changes to your files in VS Code.

4. **Stage Your Changes**
   - Click on the Source Control icon in the Activity Bar on the side of VS Code. This will open the Source Control view.
   - You will see a list of changes you made. To stage your changes, click on the `+` sign next to each file in the changes list.

5. **Commit Your Changes**
   - In the Source Control view, there is a text box at the top where you can enter your commit message.
   - After entering your commit message, press `Commit` to commit the changes.

6. **Push Your Changes**
   - Go back to the terminal in VS Code.
   - Use the command `git push origin your-branch-name` to push your changes to the remote repository.

Remember to replace `your-branch-name` with the actual name of your feature branch. Happy coding!

## Create Pull Request

Here's a step-by-step guide on how to create a pull request and request a review on GitHub:

1. **Push Your Branch to GitHub**
   - Before you can open a pull request, you must create a branch in your local repository, commit to it, and push that branch to a repository on GitHub.

2. **Navigate to the Original Repository**
   - Go to the repository on GitHub that you pushed to.

3. **Start a New Pull Request**
   - Click on the `New pull request` button. This button is located to the right of the Branch menu.

4. **Choose the Original and Forked Repository**
   - On the next screen, you'll see two dropdown lists: `base repository` (usually the feature branch) and `head repository` (usually the `main` branch). In this case we want to merge our feature branch into the `main` branch.

5. **Create the Pull Request**
   - After choosing the original and forked repository, click on the `Create pull request` button.

6. **Fill Out the Pull Request Form**
   - You'll need to fill out a title and description for your pull request. When you're done, click on the `Create pull request` button.

7. **Request a Review**
   - After creating the pull request, you can request a review. To do this, click on the gear icon next to `Reviewers` in the right sidebar of the pull request page. Then, select the person you want to review your pull request.

And that's it! You've created a pull request and requested a review on GitHub.