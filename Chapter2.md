## GIT Description

<p align="center">
<img align="center" height=400 src="img/chapter2/Github_main.png">
</p>

Before Git was published, SVN(SubVersion) was the main version management system in development industry. Big difference between Git and SVN is that. Git does not save the changes in the commit, but saves the whole code. 

It sounds Git is much slower than SubVersion. In fact, it is opposite, because when there were multiple commits such as 100, and wish to move to the first ccommit, we must calcuate 100 differences. This computation is unnecessary as Git saves the snapshot.

Let's check how Git keeps track the files using diagrams. This could be important for next chapters with new concepts.

</br>
After `git init` we created two files README.md debug.py. These two files were never committed and are referred as  'untracked' files
</br>


Using `git add` we 'stage' two files. Now files are changed from 'untracked' to 'staged'

Using `git commit`, files are now moved to 'unmodified'. We created a snapshot/version These 'unmodified' files can be modified

Using `git push`, we can upload files from local repository to remote repository. Now other people can also edit these files