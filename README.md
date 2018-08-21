# String-Variables
Python 3.7.0 (v3.7.0:1bf9cc5093, Jun 26 2018, 23:26:24) 
[Clang 6.0 (clang-600.0.57)] on darwin
Type "copyright", "credits" or "license()" for more information.
>>> greeting = "Hello World"
>>> activity = "Python Programming"
>>> 
>>> print(greeting, activity)
Hello World Python Programming
>>> print(greeting[0])
H
>>> print(greeting[1])
e
>>> pritn(greeting,"\n", activity)
Traceback (most recent call last):
  File "<pyshell#6>", line 1, in <module>
    pritn(greeting,"\n", activity)
NameError: name 'pritn' is not defined
>>> print(greeting, "\n", activity)
Hello World 
 Python Programming
>>> print(greeting, "\t", activity)
Hello World 	 Python Programming
>>> print("Journey\nReo Speedwagon\nForeginer")
Journey
Reo Speedwagon
Foreginer
>>> print("AVA\tBlinkn182\tWeezer)
SyntaxError: EOL while scanning string literal
>>> print("AVA\tBlinkn182\tWeezer")
AVA	Blinkn182	Weezer
>>> 
