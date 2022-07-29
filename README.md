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

I then updated the code so that it would also output the number of rolls it performed in order to get snake eyes. 

```
import random

roll1 = random.randint(1,6)
roll2 = random.randint(1,6)
roll_count = 1

while roll1 != 1 or roll2 !=1:
    print (roll1, roll2)
    roll1 = random.randint(1,6)
    roll2 = random.randint(1,6)
    roll_count += 1

print(roll1, roll2)
print("YAY! SNAKE EYES!!")
print(f"It took {roll_count} rolls")
```

<img width="757" alt="Screen Shot 2022-07-29 at 3 02 12 PM" src="https://user-images.githubusercontent.com/66803124/181827176-c8e0e396-41d6-4919-b4b4-81928511b383.png">

<img width="540" alt="Screen Shot 2022-07-29 at 3 02 29 PM" src="https://user-images.githubusercontent.com/66803124/181827221-a57f0725-d34b-4894-b579-a8cfc00bb441.png">

As you can see, this can vary GREATLY. 
