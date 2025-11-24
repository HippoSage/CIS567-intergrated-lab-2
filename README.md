# CIS567-intergrated-lab-2
Week 7 Lab
# Read the input: a character and the rest of the phrase
user_input = input()

# First character is the one to search for
search_char = user_input[0]

# The rest of the string (after the space) is the phrase
phrase = user_input[2:]

# Count occurrences
count = phrase.count(search_char)

# Decide pluralization
if count == 1:
    print(f'{count} {search_char}')
else:
    print(f"{count} {search_char}'s")

