the simple todo package

adding todos to a latex file
creating a table of todos
show the position in the source of the todo
show the filename of the file the todo was added

------------------
Stefan Flöser

------------------
Copyright 2015 Stefan Flöser

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
of this license or (at your option) any later version.
The latest version of this license is in
  http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions of LaTeX
version 2005/12/01 or later.

-------------------------------------------------------------------------
the sfsimpletodo package consists of the following files:
sfsimpletodo.sty

-------------------------------------------------------------------------
It adds the following two commands:
\TODO{todotext} % creates a todo 
\makeTODOList % adds a table of todos here

It has the following options:
visible=false/true - makes the todos and the table of todos visible/invisible
source - adds the source file to the todo
line - adds the source line number to the todo
nobreak=false/true - creates a linebreak before the todo
nocontent=true/false - if true the table of todos is invisible
notodo=true/false - if true the todos within the text are invisible
nointerpretation - makros within the todo command aren't executed


--------------------------------------------------------------------------
If you have any ideas, questions, suggestions or bugs to report, please
feel free to contact me.
-------------------------------------------------------------------------- 
