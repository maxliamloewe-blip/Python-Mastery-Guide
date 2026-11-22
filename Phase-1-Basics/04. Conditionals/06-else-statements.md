else 


# Function

The else conditional excutes an action without a condition.Therefore it set as the last statement.


# Syntax & Execution:

#( : ) at the end ( 1 )

#The actions automaticly go under the condition ( 2 )

# Example:

#( 1 ) & ( 2 )

points = int(input("Enter your exam score: "))

if points <= 100  and >= 85:

    print("You have an A")

elif points <= 84 and points >= 70:

     print("You have a B

elif points <= 69 and points >= 55:

     print("You have a C")

elif points <= 54 and points >= 40:

      print("You have a D")

elif points <= 39 and points >= 25:

      print("You have an E")

else:

      print("You have failed the exam")

#This is the same example as in 05-elif-statements.md

#As you can see, every point score that does'nt fit inside the if and elif statements, get procesed by else:
