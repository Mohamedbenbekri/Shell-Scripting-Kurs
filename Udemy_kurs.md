# Udemy Kurs

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

### Man kann auch ein Command als Variable nehmen 
Server_Name =$(hostname)
echo "you are running this script on ${Server_NAME}."

Output--> name von Server abfragen also der Befehl ausführen 


### Tests
#### wenn man etwas testen will [ condition-to-test-for ]
Beispiel [ -e /etc/passwd ] == überpruft ob der Datei existiert

### File Operator für Tests

[-d File ] True wenn der Path ein Verzeischniss ist 
[-e File ] True wenn existiert
[-f File ] True wenn regular Datei existiert und ist
[-r File ]  True wenn der Datei Readable ist
[-s File ] True wenn Datei existiert und nicht leer
[-w File ] True wenn Datei writable bei dir ist
[-x File ] True wenn Datei executable bei dir ist 



