# Presentations and CVs

## Instructions

### Part 1

For this assignment, you will create a set of slides in at least two different programs -- one that requires knitr (so a LaTeX based slide deck) and one that requires Rmarkdown. You may pick any of the libraries mentioned in the textbook or any modules you discover online. 

In your slides, I'd like you to introduce yourself, provide some basic biographical information (birthday, where you grew up, what program you're in, and when you expect to graduate). On subsequent slides, you should provide:

1. A picture of your favorite animal
2. Your favorite plot (can be one you've already generated in this class), which should be generated as part of your document (you can't just include the picture). 
3. A link to your CV, which you will create in the next part.

You should not show any code, automatically generated error messages, etc. in your generated files - you should only show the end product.

These slide decks should have at most 5 slides (title, introduction, animal picture, plot, and CV link), so hopefully they won't take too  much time. The goal of the assignment is that you will be familiar with the advantages and disadvantages of each slide ecosystem.

### Part 2

Use one of the CV packages mentioned in the textbook (or another LaTeX or markdown CV package that you want to try) to create a basic CV. I will not be grading the CV on how much content there is, so don't worry if you don't have publications, etc. You can add a fake publication if you want, just put the title as XXX sample XXX or something. 
You can customize your CV as you like -- it's a good idea to keep your CV up to date, so take the time to do that now if you want.

Another good source for CV templates is [Overleaf](https://www.overleaf.com/latex/templates/tagged/cv)

### Part 3

Use GitHub pages to host your CV and slide decks, following the gifs in the textbook. Create an Rmarkdown document in this repository (call it index.Rmd) with links to both of your slide decks and your CV (note: you will need to use the username.github.io links for this to work correctly). 

Some things to keep in mind:

- You don't need to commit every file latex/markdown generates: only commit the essentials: 
    - source document, 
    - any file dependencies (like pictures or data), and 
    - the final result (if you are planning to make the final result available online). 
    
- XeLaTeX allows you to use different fonts, but may cause compilation errors if you use e.g. beamer templates not designed to be compiled with XeLaTeX. You can change which engine is used by going to Project Options in RStudio.

- When you ask for help, remember to make your question as reproducible as possible!

Upload the link to the compiled index.html file to Canvas to complete this assignment.
