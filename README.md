## Bash Cheatsheet

https://devhints.io/bash

## My local bin

mv update.sh /home/noyes/bin/

## Bash Basics
https://youtube.com/watch?v=e7BufAVwDiM

## Start File With 'SheBang'

#! /bin/bash

## Redirect to file

echo "this will be 'echo'ed into file.txt" > file.txt 

cat > file.txt

## Single Line Comment with a Hash 

#

## Multi Line Comment with a Colon and Single Quotation Marks

: '

'

##hereDoc
## when this is ran the program will cat out 'this is here doc shit'
## ANYTHING can be called anything, it is the hereDoc thing. When the program runs
## the hereDoc variable (ANYTHING) tells the program where to open and close

cat << ANYTHING 
this is here doc shit
ANYTHING

## Conditional Logic

IF
IF-ELSE
ELIF
AND
OR
CASE
WHILE LOOP
UNTIL LOOP
FOR LOOP

## BREAK And CONTINUE 

Break will exit from 
Continue will 'continue' to the next line of the program 


## STDIN (Script Input)

anyScript.sh = echo $0 $1 $2 $3 $4

./anyScript.sh ANY THING AT ALL

Running the above line will output:

anyscript.sh ANY THING AT ALL
   (as $0)  ($1) ($2)($3)($4)





STDOUT and STDERR (Script Output)

Pipes (Sends output from one script to another script)
Strings processing 

Numbers and Arithmetic

Convert numbers from hex the dec

DECLARE command
Arrays
Functions
Files and Directories
Sending Email Via Script

