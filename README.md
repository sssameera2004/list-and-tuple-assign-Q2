from typing import ValuesView
asciidict = dict()
for i in range(97,123):
asciidict[chr(i)]=i
key=asciidict.keys()
value=asciidict.values()
print(‘ASCII Dict:’, asciidict)
n= str(input(‘enter the key—>’))
print(‘key:’, n)
print(‘value:’, asciidict[n])

Method 2:-
asciidict = dict()
alfapetTeller = range(97,123)
for i in alfapetTeller:
    asciidict[str(i)] = chr(i)
print(asciidict)
Method 3:-
This program prints ASCII value of all 255 characters:
print("ASCII\tCharacter")
for i in range(256):
    ch = chr(i)
    print(i, "\t\t", ch)
Method 4:-
This program prints ASCII value of the entered characters:
print("Enter a Character: ")
ch = input()
asc = ord(ch)
print("\nASCII Value:", asc)

