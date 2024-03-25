1. Create a new directory in your environment called "new-project".

       git init new-project

2. Change to the "new-project" directory.

        cd new-project
 
3. Initialize a new public Git repository inside the "new-project" directory.
        git init .

4.   Create a new file named "README.md" and add the initial text to it.
        touch README.md
        echo "example text" >> README.md
         cat README.md

5. Prepare the file "README.md" for the commit. 
         git add README.md
         git commit -m "add README file for devs"
   
6. Create a new branch named "development" and move to it.
         git checkout -b development

7. Add the instructions to the "README.md" file and prepare them for the commit.
         echo "example text" >> README.md

8. Commit the changes to the "development" branch with a commit message.    
         git commit -m "add README file for devs"
 
9. Merge the changes from the "development" branch into the "main" branch.
         git checkout main
10. Check the status, make sure everything is up to date.
    Push the changes to the new branch

        git push new-project main
        git remote add origin https://github.com/gbrgiyo/new-project.git
        git push new-project main
        git push -u origin main
