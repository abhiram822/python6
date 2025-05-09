# python6
basic calculator using while condition
while True:
    n1=int(input("enter the first value:"))
    n2=int(input("enter the second value:"))
    op=input("enter the operation symbol:")
    if op=="+":
        print(f'addition of two numbers={n1+n2}')
    elif op=="-":
        print(f'subtraction of two numbers={n1-n2}')
    elif op=="*":
        print(f'multiplication of two numbers={n1*n2}')
    elif op=="/":
        print(f'division of two numbers{n1/n2}')
    elif op=="**":
        print(f'square of two numbers={n1**n2}')
    elif op=="//":
        print(f'floor division of two numbers={n1//n2}')
    elif op=="%":
        print(f'module of two numbers={n1%n2}')
    else:
        print("not a basic operatin")
        
