print(type(name))
print("\nHello,", name + "!")
print("Welcome to the Mad Libs Game!")
print("Fill in the blanks below to create your funny story.\n")

adjective = input("Enter an adjective: ")
noun = input("Enter a noun: ")
food = input("Enter a type of food: ")
animal = input("Enter an animal: ")
verb = input("Enter a verb ending with -ing: ")
place = input("Enter a place: ")

story = f"""
One day, a {adjective} {noun} was walking to {place}.
He was super hungry and wanted to eat some {food}.
Suddenly, a {animal} appeared and started {verb} {noun}  loudly!
Everyone around started laughing.
In the end, the {noun} and the {animal} became best friends.
They opened a restaurant in {place} that served only {food}!
"""

print("\nHere’s your funny story!")
print(story)
