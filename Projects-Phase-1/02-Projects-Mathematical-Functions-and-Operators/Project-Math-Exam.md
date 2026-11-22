# Math Exam

# Code:

print("Python-Math-Exam")
total = 0
print()
task_1 = int(input("What is 2 + 2: "))
print()
if task_1 == 4:
    print("Correct")
    total += 1
else:
     print("Wrong")
print()
task_2 = int(input("What is 3 - 5: "))
print()
if task_2 == -2:
    print("Correct")
    total += 1
else:
    print("Wrong")    
print()
task_3 = float(input("What is 10 / 2: "))
print()
if task_3 == 5.0:
    print("Correct")
    total += 1
else:
    print("Wrong")
print()
task_4 = int(input("What is 6 % 2.5: "))
print()
if task_4 == 1:
    print("Correct")
    total += 1
else:
    print("Wrong")
print()
task_5 = int(input("What is 3 ** 3: "))
print()
if task_5 == 27:
    print("Correct")
    total += 1
else:
    print("Wrong")
print()
if total < 3 and total >= 0:
    score = "You failed the exam"
elif total >= 3 and total <= 5:
    score = "You passed the exam"
print("Your exam score: 5/" + str(total) )
print()
print(score)    

