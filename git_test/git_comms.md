* git cat-file -p <hash>    //log file contents //   //find hash git log//
* git config --add --local  //author info, etc//
*            --unset   //remove value//
*            --remove -section   //remove entire section//
* git switch -c new_branch    //create & switch to new branch//
* git branch    //see you current branch, marked with *//
* git log --decorate =full   //commit history with additional info
*                    =no
*                    =short 
* git log --oneline   //compact commit history
* git log --oneline --graph --all   //full commit & branch history//
* git log --graph
* git log --all
* 
*
* git merge <branch_to_merge>  //no merge commit created//  //must be on the branch into which we are going to merge//
* git commit --amend -m "new commit message""   //amend old commit message with the new message//
* git branch -D <branch_name> //delete selected branch//
* git log --grep=<text_input_from_commit_message>  //will search for matching words inside commit messages//
* git reset --soft <commit-hash>  //will return you back from the current commit to the commit with the hash provided 
* git checkout <commit-hash> -- file_name.md  //will checkout file from the tree  that is if you want previous version file, unmodified, etc
