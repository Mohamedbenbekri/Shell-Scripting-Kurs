# Titel

### Variable

echo “ hello “>newtext.txt   = speichert der Text unter newtext datei
echo “ hello “>>newtext.txt   = fügt zusätzlich der Text unter newtext datei

#!/bin/bash   = to tell Linux this is Bash = Shebang

My_Shell=”bash”
echo” this is ${MY_Shell}”   Output this is bash

-Eeuo = -e stoppt Script sofort bei Fehler  -um Fehler wenn Variable nicht existiert -E trap funktioniert auch in Funktione


if [-d”Path”]   = Wenn Datei existiert    if[!-d “Path”]  = Wenn Datei nicht existiert


./… = wenn der Datei nicht in Path ist


#! /bin/.. = shebang wählt der Interpretuer aus 
Aber wenn keine Shebang gibt wird Default shell genutzt


Variable : 

MY_SHELL=”bash”
echo”I like $MY_SHELL shell “

