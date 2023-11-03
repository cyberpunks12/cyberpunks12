import random
import string

def generate_random_password(length=6):
    characters = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(random.choice(characters) for _ in range(30))
    return password

if __name__ == '__main__':
    random_password = generate_random_password()
    print("Generated Password:", random_password)
