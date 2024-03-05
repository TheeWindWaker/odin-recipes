# Odin Project - Foundations Project: Recipe Webpage

[Project: Recipes](https://www.theodinproject.com/lessons/foundations-recipes)

[Project: Revisiting Recipes (CSS Addition)](https://www.theodinproject.com/lessons/foundations-the-cascade#assignment)

[Block & Inline (CSS Block Addition)](https://www.theodinproject.com/lessons/foundations-block-and-inline)

## Objective
### Project Recipes
- Build a basic recipe website using knowledge from previous lessons
- make use of git, github, terminal commands and HTML
- Make commits early and often to keep track of large changes
- use git commit with messages following the "7 rules of a good commit message" from a previous lesson

### Project: Revisiting Recipes (CSS Addition)
- Add CSS styling to the Recipe Page (color, background, buttons etc.)
- Make use of specificity and applying styling to multiple pages using the single CSS stylesheet

### Project: Block and Inline (CSS Addition)
- Add further graphic updates to the recipe pages using the box model


## Lessons Learned
-  If you are not sure if you are in the proper git project, navigate to the folder in the terminal, and enter 'git init'. If there is a git project associated with that folder, it will automatically initialize for that project.
- Indenting paragraphs is not done for websites.
- Had an issue where when I added a file from the recipe folder, it would not show up in git log, but files in the images folder would.
	- the solution was to remove the .git folder in the recipes folder using `rm -rf recipes/.git` command and then `git add .` command to make everything on the main branch.
	- I believe this is something called a `submodule`.
- `rel="noopener noreferrer"` not required for local links.
- Remember to use 'box-sizing: border box' when trying to contain a box in a container without having to manually adjust the dimensions.
- When making a list using ol or ul, the bullets/numbering are contained outside of the box by default and in the padding of the element instead.
	- in the styles.css here, a margin was added to keep the list in the desired block area. 



## Versioning

## Authors
- Nikesh Patel

## Acknowledgements
- The Odin Project
