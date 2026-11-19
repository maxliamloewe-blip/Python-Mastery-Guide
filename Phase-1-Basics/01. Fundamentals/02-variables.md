# Variables


# Funktion:

#Variables allow you to store data, by using  = 

# Syntax & Execution

#Gaps are closed by typing _ ( 1 )

#Newest change holds the current value ( 2 )

#Combining a value with a variable ( 3 )

#Adding variables with each other ( 4 )

#Variables inside variables ( 5 )

#Multiple assignment ( 6 )

# Examples

name = "Ben"
print( name )

#Prints Ben 

#( 1 )

first name = "Ben

#Wrong way

first_name = "Ben"

#Correct way

#( 2 )

name = "Ben"
name = "Sam"
print( name )

#Prints Sam , since the newest holds the current value

#( 3 )

food = "pizza"

print( "I like " + food )

#Prints I like pizza
#Values need to have the same type. More of that in 03.types.md

#( 4 )

like = "I like: "
what_do_you_like = "basketball"
print( like + what_do_you_like )

#Prints I like: basketball

#( 5 )

number_a = number_b = number_c = 100

#Each of these e variables hold the value 100

#( 6 )

name,age = "Ben",16
print("Name: " + name )
print("Age: " + age )

#Prints 
#Name: Ben
#Age: 16
#You can assign values to multiple variables in one line, by using ,
