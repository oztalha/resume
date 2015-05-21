# Markdown Resume

Creating your PDF resume from Markdown is just two steps:

1. Convert the `.MD` file to `.tex`: `pandoc resume.md -o resume.tex`
2. Convert the `toz.tex` to `.PDF` with a single click using TexWorks (choose XeLaTeX).

Note #1: I hardcoded the `resume.tex` **filename** using the `input` command into `toz.tex`. So, if your Markdown output (`resume.tex` file) is named `myresume.tex`, then change the line `\input{resume}` in the `toz.tex` wrapper file to `\input{myresume}`. 

Note #2:  Step 2 simply could have been something like `pandoc -s toz.tex -o resume.pdf` but this command as is fails. If you know how to make it work please let me know.

Here is the original [blog post](http://craigeley.com/09-05-2013/formatting-your-cv-with-markdown-and-latex/)
on *Formatting Your CV with Markdown and LaTeX* by Craig Eley. 

