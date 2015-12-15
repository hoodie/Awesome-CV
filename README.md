Awesome CV
==========

This is a LaTeX CV template originally written by [posquit0](https://github.com/posquit0/Awesome-CV). 
I use the modified version of [missCarrieMah](https://github.com/missCarrieMah/Awesome-CV) and adapted it a bit.

## Modifications
* Increased line space in skill section
* Changed colors

## TODO
Create a cover letter


Parts of the Original Documentation
==========

## How to Use
### Requirements

You have to install fundamental latex packages on system including xelatex. Also, Awesome-CV uses [Font Awesome](http://fortawesome.github.io/Font-Awesome/) to draw icons. You have to install on system.

#### Ubuntu(Debian)
```bash
$ sudo apt-get install texlive texlive-latex-extra texlive-xetex texlive-math-extra
```

```bash
$ sudo apt-get install fonts-font-awesome
```

#### Install Source Sans Pro Font
```bash
$ sudo wget https://github.com/adobe-fonts/source-sans-pro/archive/2.010R-ro/1.065R-it.tar.gz
$ tar -xvf 1.065R-it.tar.gz
$ mkdir -p ~/.fonts
$ cp source-sans-pro-2.010R-ro-1.065R-it/OTF/*.otf ~/.fonts/
$ fc-cache -f -v
```

### Usage

In Linux run
```bash
$ xelatex {your-cv}.tex
```
This should result in the creation of ``{your-cv}.pdf``


## Credit
### LaTeX
Latex is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia.

You can find out more about it here: [LaTex Project](http://www.latex-project.org/)

### LaTex-FontAwesome
[Latex FontAwesome](https://github.com/furl/latex-fontawesome) is bindings for FontAwesome icons to be used in XeLaTeX.

### Source Sans Pro
[Source Sans Pro](https://github.com/adobe-fonts/source-sans-pro)  is a set of OpenType fonts that have been designed to work well in user interface (UI) environments.


## Contact
You are free to take my .tex file and modify it to create your own resume. Please don't use my resume for anything else without my permission, though!

If you have any questions, feel free to join me at [`#posquit0` on Freenode](irc://irc.freenode.net/posquit0) and ask away. Click [here](https://kiwiirc.com/client/irc.freenode.net/posquit0) to connect.

Good luck!
