## PART 1: The Basics
_(based on tsct-demo1)_

TASK 1.1: Provide the following pieces of information:
    - Author of the first commit = ?
    - Hash of the "root" tree = ?
    - Hash of blob of _commands.txt_'s content = ?
    - Number of branches demo1 has (can't use _git branch_) = ?

TASK 1.2: Recover a dangling commit
    - Tag your current position
    - Commit a random change
    - Revert that change on a new commit (CX)
    - Reset (--hard) to your Tag
    - Restore your CX. Is CX lost?


## PART 2: Branching
_(based on tsct-demo2)_

TASK 2.1: Merge a conflicting branch

TASK 2.2: Rebase of Hamburguer
    - Checkout master
    - Commit file *00_bread.txt*
    - Rebase branch hamburguer onto master
    - Commit last "bread" file and push

TASK 2.3: Interactive rebase
    - Rewrite branch *rebasei* so as to have a log like:
        - Add file4
        - Add file3
        - Add file2
        - Add file1

## PART 3: Above and Beyond
_(based on tsct-demo3)_

TASK 3.1: Multiple Remotes
    - Clone tsct-demo3
    - Create a new repository (R2) on your online git hosting
    - Push to R2 the content demo3

TASK 3.2: Apply and Create patches
    - Checkout master
    - Add to 2 new commits
    - Create a patch of those commits
    - Exchange patches with a partner
    - Reset to master and apply the patch you where given
