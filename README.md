# Dumpe_StudentInfoFormatter
Version 1 :
first_name = input("Enter first name: ") 
last_name = input("Enter last name: ") 
section = input("Enter section: ") 
favorite subject = input("Enter favorite subject: ")

print()
print("Formatted Output: ) 
print("Name: ", first_name, last_name) 
print("Name Code: ", first_name, last_name)
print("Section: ", section)
print("Favorite subject: ", favorite_subject)

# Version 2: Added string formatting methods and character count
first_name = input("Enter first name: ")
last_name = input("Enter last name: ")
section = input("Enter sectiom: ")
favorite_subject = input("Enter favorite subject: ")

# Combine first and last name with a space in between
full_name = first_name + " " + last_name

print()
print("Formatted Output:")
print("Name:", full_name.title())
print("Name Code:", full_name.upper())
print("Section:", section.upper())
print("Favorite Subject:", favorite_subject.title())
print("Character Count:", len(full_name))
