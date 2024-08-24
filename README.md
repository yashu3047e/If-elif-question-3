# If-elif-question-3
# WAP to enter two number and ask the operator (+ - * / ) from the user and display the result by applying operator on the two number

num1 = int(input("Enter First Number : "))
num2 = int(input("Enter Second Nuber ; "))
a = input("Enter the Operator For the two number [+,-,/,*] : ")
if a=='+':
    print("The Sum Of Two Number : ", num1+num2)
    
elif a=='*':
    print("Multiplication Of two number : ", num1*num2)
    
elif a=='/':
    print("Divison Of Two Numbers : ", num1/num2)
    
elif a=='-':
    print("Substraction Of Two Number : ", num1-num2)
    
else:
    print("Error, Try Again!! With Int digits")
