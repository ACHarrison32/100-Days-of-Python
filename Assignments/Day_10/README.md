```cpp
myBill = float(input("What was the bill?: "))
tipAmount = float(input("How much would you like to tip?: "))
numberOfPeople = int(input("How many people?: "))
totalBill = myBill + tipAmount
answer = totalBill/numberOfPeople
answer = round(answer, 2)
print("You each owe:", answer)
```
