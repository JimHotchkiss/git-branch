# Git branch workflow
1.) 'git pull' - Get the most current version of the master branch
2.) 'git branch' - List all the branches
3.) 'git branch <name of branch>'
4.) 'git checkout <name of branch>' - This will switch over to the created branch

# Now you can preform work on this new branch without touching the main branch

<<<<<<< HEAD
5.) 'git add . ', 'git commit -m "", 'git push' - To commit changes to newly created branch
6.) 'git pull' - This pushes the code to the reposity for review
    * First you want to checkout to the main branch
    * Do a 'git pull' - Here you're looking for changes to the main branch
    * 'git checkout <name of branch>' - Now merge with main branch
    * 'git merge main'
        - You may have conflicts you have to resolve. Once resolved go back to <name of branch> 
    * 'git push' - You'll be asked to 'set upstream to=...'
        - With this message, git is saying it doesn't know where to push it to. You can cut and paste the set upstream command
# Now you can go to the repository and see two branches. You'll also see 'Compare and Pull Request'
=======

5.) 'git add . ', 'git commit -m "", 'git push' - To commit changes to newly created branch






>>>>>>> 2a187ecd20a1b5356ed253a8bcffd2762398b0d7
