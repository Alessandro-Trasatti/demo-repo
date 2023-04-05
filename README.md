# Demo

This is generally a markdown file that is present in every repository.
Usually, this describes the code/projects that are present in this repository.
As you can see, there are **plenty** of shortcuts that you can use. It should work the same as in any Jupyter notebook.
For instance you can type equations:
$$e^{i\pi} = -1$$

First thing first, we pulled from the Github repository using the command <code>git clone</code>, copying the ssh. address. Now, I changed the file locally. This can be checked using the command <code>git status</code>. In fact I modified the *README.md* file and I added *test.cpp*. If I want to add all these files (in general *every file*) just run the command

                        git add .
If you want to add just a file, for instance just *test.cpp*, the command is the following

                     git add test.cpp
After adding the files, it is important to commit them. To do that, use

                      git commit -m
To push these changes to a remote repository, that in Git Hub for instance, we use the command

                    git push origin master
The *origin* keyword is a word taht stands for the location of our git repository. The keyword *master* (try *main* instead of *master* if it doesn't work) stands for the branch we want our changes to be pushed to.