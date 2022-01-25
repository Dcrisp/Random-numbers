import random
# dice roll
Roll = random.randrange(1, 20)
txt = "You roll the dice....you rolled a {}"
print(txt.format(Roll))
# Random item from a chest 
Treasurelist = ["Strange ring", "Dagger", "Rusted sword", "Precious gem", "Mysterious note"]
txtc = "You open the chest and find a {}"
print(txtc.format(Treasurelist[random.randrange(1,5)]))
