# Dictionary-Activities

# Activity 1: Fill in the Blanks
student = {
    "name": "Ana",
    "age": 20,
    "course": "IT"
}

print(student["name"])

# Activity 2: Add and Update
student = {"name": "Ana", "age": 20}

student["grade"] = 95
student["age"] = 21

print(student)

# Activity 3: Loop Through Dictionary
car = {"brand": "Toyota", "model": "Corolla", "year": 2020}

for key, value in car.items():
    print(key, ":", value)
    
# Activity 4: Mini Phonebook
phonebook = {
    "Cedric": "09162173629",
    "Charlz": "09939025809",
    "Marcial": "09925583351", 
    "Jerone": "09389386772"
}

name = input("Enter name: ")
print(phonebook.get(name))
