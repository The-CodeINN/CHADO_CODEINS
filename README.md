# CHADO_CODEINS
# Function to add numbers
def add(x,y):
    return x+y

# function to subtract numbers
def subtract(x,y):
    return x-y

#function to multipy numbers
def multiply(x,y):
    return x*y

#function to divide numbers
def divide(x,y):
    return x/y

print('Select operation:' '\n1. Add' '\n2. Subtract' '\n3. Divide' '\n4. Multiply')

while True:
    #Input from user
    choice = input('Enter choice 1-2-3-4:')
    
    #checking if choice is in one of these inputs
    if choice in ('1', '2', '3', '4'):
        num1 = float(input('Enter first number: '))
        num2 = float(input('Enter second number: '))
        
        if choice == '1':
            print(num1, '+', num2, '=', add (num1, num2))
            
        elif choice == '2':
            print(num1, '-', num2, '=', subtract (num1, num2))
            
        elif choice == '3':
            print(num1, '*', num2, '=', multiply (num1, num2))
            
        elif choice == '4':
            print(num1, '/', num2, '=', multiply (num1, num2))
            
        break
        
    else:
        print('Invalid input')
