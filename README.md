# Function to greet the user
def greet_user(username):
    print(f"\nWelcome, {username}! Let's explore some Python basics together.\n")

# Function to check if the user is an adult
def check_age(age):
    if age >= 18:
        return "You are an adult!"
    else:
        return "You are not an adult yet."

# Function to demonstrate basic loops and conditionals
def basic_loop():
    print("\nCounting from 1 to 5:")
    for i in range(1, 6):
        print(i)

# Function to reverse a string
def reverse_string(text):
    return text[::-1]

# Function to demonstrate basic list operations
def list_operations():
    fruits = ["apple", "banana", "cherry", "date"]
    print("\nOriginal list of fruits:", fruits)

    # Adding a new item to the list
    fruits.append("elderberry")
    print("After adding elderberry:", fruits)

    # Removing an item from the list
    fruits.remove("banana")
    print("After removing banana:", fruits)

    # Reversing the list
    fruits.reverse()
    print("Reversed list:", fruits)

# Main function to execute the program
def main():
    # Getting user input
    name = input("Enter your name: ")
    age = int(input("Enter your age: "))

    # Greeting the user
    greet_user(name)

    # Checking if the user is an adult
    result = check_age(age)
    print(result)

    # Demonstrating a basic loop
    basic_loop()

    # Reversing a string
    text = input("\nEnter a string to reverse: ")
    reversed_text = reverse_string(text)
    print(f"Reversed string: {reversed_text}")

    # Demonstrating basic list operations
    list_operations()

# Run the program
if __name__ == "__main__":
    main()
