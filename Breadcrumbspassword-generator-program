""" Password Generator Program ----> Supriyo Das """

import string
import random

def generate_password(strength):
    password = []
    if strength.lower() == 's' or strength.lower() == 'strong':
        length = 10
    elif strength.lower() == 'w' or strength.lower() == 'weak':
        length = 6
    else:
        return "Incorrect option. Please try again!"

    combine = string.punctuation + string.digits + string.ascii_letters
    for _ in range(length):
        random_choice = random.choice(combine)
        password.append(random_choice)
    return ''.join(password)

print("Welcome to the Password Generator program ---> Dilpreet Singh Kohli\n")

option = input("Please enter how strong you would like your password to be: (S - Strong) or (W - Weak): ").capitalize()

generated_password = generate_password(option)
print("Generated Password:", generated_password)
