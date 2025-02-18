# Notes for the CSE Course at PESU

These notes were written in LaTeX and compiled over the course of 6 semesters of the
Computer Science and Engineering course at PES University, Bengaluru, India.

The notes are organized into 2 folders, namely ```src``` and ```pdf```

The ```pdf``` folder contains the PDF versions of all the notes. You can use these directly 
by simply cloning this repo and opening the file you want.

The ```src``` folder contains the TeX source code (as well as image files in case
 the file contains images) for each individual PDF file organized in
the same way. I kindly encourage you to fork this repo and modify the notes
 as time goes on and the course contents are updated, as well as add the courses 
that you have taken (electives). 

You can compile the TeX files on your own machine or use Overleaf (like I did!)

Follow the below instructions only if you want to install on your machine

# LaTeX installation instructions

## On Linux

Install texlive using:

For Debian/Ubuntu/Pop!_OS users:

```console
$ sudo apt install texlive
```

For Fedora users:

```console
$ sudo dnf install texlive-scheme-medium
```

For the "btw I use Arch" gang:
```console
$ sudo pacman -S texlive-core 
```

Commands to generate PDF files on all are the same:

```console
$ pdflatex <file path>.tex
```
## On macOS

You can use [MacTeX](https://tug.org/mactex/) which is simple to install

# On Windows

I recommend [MiKTeX](https://miktex.org/)
