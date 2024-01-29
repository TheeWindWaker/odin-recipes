# Odin Project - Foundations Project: Recipe Webpage

[Project: Recipes](https://www.theodinproject.com/lessons/foundations-recipes)

## Objective:
- Build a basic recipe website using knowledge from previous lessons
- make use of git, github, terminal commands and HTML
- Make commits early and often to keep track of large changes
- use git commit with messages following the "7 rules of a good commit message" from a previous lesson

## Lessons Learned
-  If you are not sure if you are in the proper git project, navigate to the folder in the terminal, and enter 'git init'. If there is a git project associated with that folder, it will automatically initialize for that project.
- Indenting paragraphs is not done for websites.
- Had an issue where when I added a file from the recipe folder, it would not show up in git log, but files in the images folder would.
	- the solution was to remove the .git folder in the recipes folder using `rm -rf recipes/.git` command and then `git add .` command to make everything on the main branch.
	- I believe this is something called a `submodule`.
- `rel="noopener noreferrer"` not required for local links
- 



## Versioning

## Authors
- Nikesh Patel

## Acknowledgements
- The Odin Project