```cpp
tvShow = input("What is your favorite TV show?: ")
if tvShow == "Family Guy":
  print("Family Guy is also my favorite!!!")
  favoriteCharacter = input("What is your favorite character from Family Guy?: ")
  if favoriteCharacter == "Stewie":
    print("Stewie is by far the best character")
  else:
    print("Ehhh I dont know, I think stewie is the best")
elif tvShow == "The Simpsons":
  print("Personally I'm not the biggest fan of The Simpsons")
  favoriteCharacter = input("What is your favorite character from The Simpsons?: ")
  if favoriteCharacter == "Homer":
    print("Homer is hilarious")
  elif favoriteCharacter == "Bart":
    print("Bart is very funnt. One of my favorites for sure")
else:
  print("That one's pretty good, I personally like Family Guy more though")
  ```
