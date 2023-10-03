# unix-cli

`mkdir -p hello/five/six/seven`

`touch hello/five/six/c.txt`

`touch hello/five/six/seven/error.log`

`mkdir -p hello/one/two/three/four`

`touch hello/one/a.txt`

`touch hello/one/b.txt`

`touch hello/one/two/d.txt`

`touch hello/one/two/three/e.txt`

`touch hello/one/two/three/four/access.log`


Explanation :-
1.`mkdir -p` hello/five/six/seven  : used to create directories and `-p` this will do if the parent directories do not exist, they are created as well

- `touch` hello/five/six/c.txt  :  used to create empty files.
- `hello/five/six/c.txt`: to get the path and name of the file you want to create.

`touch` hello/five/six/seven/error.log : to get the path and name of the file you want to create.log

`mkdir -p` hello/one/two/three/four 

`touch` hello/one/a.txt : Creates an empty file and to get the path and name of the file you want to create

`touch` hello/one/b.txt :  Creates an empty file and to get the path and name of the file you want to

`touch` hello/one/two/d.txt :  Creates an empty file and to get the path and name of the file you want to 

`touch` hello/one/two/three/e.txt

`touch` hello/one/two/three/four/access.log



2.`find hello -type f -name "*.log" -delete` : finding and deleting 

3.`echo` "Unix is a family of multitasking, multiuser computer operating systems that derive from the original AT&T Unix, development starting in the 1970s at the Bell Labs research center by Ken Thompson, Dennis Ritchie, and others" > `hello/uno/a.txt`

4.`rm` -r hello/five  : to delete the "five"

5.`mv` hello/one hello/uno  : Rename the "one" to "uno"

6. `mv` hello/uno/a.txt hello/uno/two/ : to move "a.txt" to the "two"

