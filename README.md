# The-sorting-hat-challenge-
The challenge on codex. 

ravenclaw = 0 
hufflepuff = 0 
slytherin = 0 

print('Get closer, let me see into that mind of yours...')

# ---------------- Q1 ----------------
print('Q1) Do you like dawn or dusk?')                       
print("  1) Dawn")
print("  2) Dusk")

answer = int(input('Enter answer (1-2): '))

if answer == 1:
   gryffindor += 1
   ravenclaw += 1
elif answer == 2:
   hufflepuff += 1
   slytherin += 1
else:
     print('Wrong input')

 # ---------------- Q2 ----------------
print("\nQ2) When I'm dead, I want people to remember me as:")
print('1 The good')
print('2 The great')
print('3 The wise')
print('4 The bold')

answer = int(input('Enter answer (1-4): '))

if answer == 1:
   hufflepuff += 2 
elif answer == 2:
   slytherin += 2
elif answer == 3:
   ravenclaw += 2
elif answer == 4:
   gryffindor += 2
else:
    print('Wrong input')

# ---------------- Q3 ----------------
print('\nQ3) Which kind of instrument most pleases your ear?')
print('1 The violin')
print('2 The trumpet') 
print('3 The piano')
print('4 The drum')

answer = int(input('Enter answer (1-4): '))

if answer == 1:
   slytherin += 4
elif answer == 2:
   hufflepuff += 4
elif answer == 3:
   ravenclaw += 4 
elif answer == 4:
   gryffindor += 4
else:
     print('Wrong input')

 # ---------------- Q4 ----------------
print('\nQ4) Who is your favourite character, in Harry Potter?')
print('1 Harry Potter')
print('2 Hermione Granger')
print('3 Ron Weasley')
print('4 Albus Dumbledore')

answer = int(input('Enter answer (1-4): '))

if answer == 1:
   ravenclaw += 5
elif answer == 2:
    gryffindor += 5 
elif answer == 3:
   hufflepuff += 5 
elif answer == 4:
   slytherin += 5 
else:
    print('Wrong input')
