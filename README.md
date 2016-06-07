## Adding and Contributing Solutions

### First Clone the Repository

The easiest way to download the needed files is to clone the entire repository from your personal account. You will need to install [Git](https://help.github.com/articles/set-up-git) for this. 

```
git clone https://github.com/adelphimathcs/ProjectEuler
```

###Adding a New Solution

To add a new solution, first see if the problem number that you are solving already exists in the repository. If it does not exist, create it.  If it does exist, create a folder in it. The folder should be the name of the programming language you wrote the solution in. If that folder already exists, put your files in there. If your solution is a mathematical write up, you can write it in a README.md file or post a write-up in LaTeX. If you choose LaTeX, make sure and post the source files, and not just the PDF.

Now that you have added your solution locally, you need to push it to the main repository. 
```
git add ./*
git commit -a -m 'message explaining what you added'
git push origin master
```


### Contribute to Existing Solutions

While anyone has the ability to modify existing files, it is best if you use GitHub's `issues` to discuss the changes with the original author before making any modifications. To modify the files, you only need to clone the repository, make changes, and then push your commits as above. 




