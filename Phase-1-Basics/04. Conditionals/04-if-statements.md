# if statements 


# Function:

#Executes an action, if the condition is right

# Syntax & Execution:

#( : ) at the of the if statement ( 1 )

#Following actions are positioned under the condition ( 2 )

#Adding and, or ( 3 )

# Example:

#( 1 ) & ( 2 )

age = int(input("Enter your age: "))

if age => 18:

    print("You may enter")

#Prints You may enter, if the user input is 18 and over

#The ( : ) is the final piece for the if statement to function

#The action automaticly goes under the confution, in this instance the age variable

#( 3 )

temperature = 20

if temperature > 0 and temperature < 30:

    print("The temperature is optimal")

if temperature < 0 or temperature > 30:

    print("The weather is not optimal")

#and proves if all of the conditions are true and or proves if one of the conditions is true.
