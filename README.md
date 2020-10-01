# FAULTY CALCULATOR

print("enter the 1st number")
n1 = int(input())
print("slect the operation:")
n3 = input()
print("enter the 2nd number")
n2 = int(input())

if n1==45 and n3=='*' and n2==3:
    print("555")
elif n1==56 and n3=='+' and n2==9:
    print("77")
elif n1==56 and n3=='/' and n2==4:
    print("4")
elif n3=='+':
    print("=", n1+n2)
elif n3=='-':
    print("=", n1-n2)
elif n3=='*':
    print("=", n1*n2)
elif n3=='/':
    print("=", n1/n2)
else:
    print("select an appropriate operator")

# THIS CALCULATOR MAY GIVE YOU THE WRONG VALUES OF THE ABOVE MENTIONED THREE VALUES/OPERATIONS
