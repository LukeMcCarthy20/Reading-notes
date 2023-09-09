# ChatBot Prep
## Notes-
***A prompt contains any of the following elements:***

**Instruction** - a specific task or instruction you want the model to perform

**Context** - external information or additional context that can steer the model to better responses

**Input Data** - the input or question that we are interested to find a response for

**Output Indicator** - the type or format of the output.
## ***Output from chatbot-***
Certainly! If you already have Git installed but want to focus on the "Add, Commit, Push" (ACP) process, we can skip the Git setup steps and jump right into the basic ACP workflow. Here's how to use Git for this process:

Navigate to Your Project Directory:

Open your terminal and navigate to your project directory using the cd command:
bash
Copy code
cd /path/to/your/project
Check the Status:

Before making changes, it's a good practice to check the status of your Git repository to see which files have been modified:
bash
Copy code
git status
Add Changes to the Staging Area:

Use the git add command to stage the changes you want to include in your next commit. You can specify individual files or use a wildcard to add all changes:
bash
Copy code
git add <file1> <file2> ...  # To add specific files
git add .                    # To add all changes
Commit Changes with a Message:

After staging your changes, commit them to your local repository with a descriptive message:
bash
Copy code
git commit -m "Your commit message here"
Push Changes to a Remote Repository:

If you're working with a remote Git repository (e.g., on GitHub), you can push your local changes to the remote repository using the git push command:

bash
Copy code
git push origin <branch_name>
Replace <branch_name> with the name of the branch you're working on (e.g., main or master).