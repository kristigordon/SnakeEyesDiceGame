# SnakeEyesDiceGame

This is a game that uses the random library to randomize two die. The program uses a while loop to roll two dice until both die simulatneously roll a one. 

```
import random

roll1 = random.randint(1,6)
roll2 = random.randint(1,6)

while roll1 != 1 or roll2 !=1:
    print (roll1, roll2)
    roll1 = random.randint(1,6)
    roll2 = random.randint(1,6)

print(roll1, roll2)
print("YAY! SNAKE EYES!!")
```

<img width="715" alt="Screen Shot 2022-07-29 at 2 57 27 PM" src="https://user-images.githubusercontent.com/66803124/181826477-741afedd-8c4b-4290-b45b-2ebada8a004d.png">
