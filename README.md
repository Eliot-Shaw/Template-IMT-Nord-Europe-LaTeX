# Template-IMT-Nord-Europe-LaTeX
Un template LaTeX pour les étudiants et professeurs (s'ils osent) correspondant aux couleurs et formes de l'IMT Nord Europe

[Petit exemple](paper/build/main.pdf)

# Installation :

`sudo apt-get install texlive-full` 
When at `Pregenerating ConTeXt MarkIV format. This may take some time...`, wait a bit and hit `Enter` a few times ;)

# Build :

`pdflatex -output-directory=paper/build paper/main.tex && pdflatex -output-directory=paper/build paper/main.tex`
