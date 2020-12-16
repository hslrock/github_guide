# Working With Other People

Now, what happends if two people work simultaneously.


If Alice works on 'first.py','second.py','thrid.py' and Bob works on 'fourth.py' at the same time. 

## How Git manages the Commit.

Git manages the 'commit' in a train manner. Single person will not create any 'crash'

New Commit always points toward the previous commit. If  two players tries to commit toward one previous  commit. It will cause an error.

*To be exact, the first person can commit without error, but the second person who does know about this new commit will face an error "You are trying to commit/push to an old code, push to the recent version.

The function that allows the train to separate into multiple tails is branch
 You might remember 'master', 'origin/master' in Chaper 0. First commiting makes a branch called 'master' to point the commit. Second commiting will make the master branch to point toward the second commit.

 Why use the term 'point'? If you are familiar with the 'pointer' concept (C language), it is similar. The branch does not physically exist, but is just pointing (???)

 Let's use diagram to explain