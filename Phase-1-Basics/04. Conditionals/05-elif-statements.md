# elif statements 


# Function:

#elif statements short for else if, allows you to include more confitions to an if statement

# Syntax & Execution:

#( : ) at the end ( 1 )

#The actions automaticly go under the condition ( 2 )

# Example:

#( 1 ) & ( 2 ) & ( 3 )

input = int(input("Enter your exam score: "))

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

elif points <= 24 and points >= 0:

      print("You have failed the exam")

#Based on your input these statements prove which grade you achieved.
