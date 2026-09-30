# Char-identifier-
ch = input("Enter a char: ")
if len(ch)==1:
  if ch.isupper():
    print(f"{ch} is uppercase")
  elif ch.islower():
    print(f"{ch} is lowercase")
else:
    print("Invalid char")