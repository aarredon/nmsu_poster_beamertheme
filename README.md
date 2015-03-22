# nmsu_beamertheme

This is a New Mexico State University research poster theme.

I've used the city naming scheme for this theme, LasCruces, where New Mexico State University main campus
is located.

## Installing a custom theme

#### Working directory
Copy the file *beamerthemeLasCruces.sty* and *colorsLasCruces.sty* to your working directory.

#### Not in working directory
If you are going to use the theme often, it is best to "install" it.  If my **$HOME** 
directory is **/home/antonio**, the path **/home/antonio/texmf/tex/latex/** must be
created if it doesn't already exist. If it exists, skip the first command.

To create the path use the following commands:
    
    mkdir -p ~/texmf/tex/latex
    cp beamerthemeLasCruces.sty ~/texmf/tex/latex/
    cp colorsLasCruces.sty ~/texmf/tex/latex/
    texhash ~/texmf/tex/latex


## Usage

Once the theme is installed, add the following lines at the top of your tex file:

    \documentclass[final]{beamer}
    ...
    \usetheme{LasCrucesPort}
    ...

### Custom content

Add the following lines to your tex file

    \newcommand{\UniName}{New Mexico State University}
    \newcommand{\UniDeptName}{Computer Science}

See lascruces_example.tex for more details.


## Screenshots

![Poster Portrait](http://www.cs.nmsu.edu/~aarredon/screenshots/lascruces_poster_portrait01.png "Poster Portrait")




