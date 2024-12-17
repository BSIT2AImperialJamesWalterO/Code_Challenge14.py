# Code_Challenge14.py
numbers = []
while True:
    try:
        num = int(input("Enter a number: "))
        if num == -7:
            break
        numbers.append(num)
    except ValueError:
        print("Invalid input. Please enter an integer.")

total = sum(numbers)
print(f"Loop has terminated. The sum of all the numbers given is {total}")
