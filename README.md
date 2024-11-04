# CIS567-integrated-lab-1
Output range with increment of 5

first_integer = int(input())
second_integer = int(input())

if second_integer < first_integer:
    print("Second integer can't be less than the first.")
else:
    current_value = first_integer
    
    
    while current_value <= second_integer:
        print(current_value, end=' ')
        current_value += 5
        
    print()  
