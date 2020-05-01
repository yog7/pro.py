# pro.py
first attempt
n=int(input("Enter number:"))
spare=n
rev=0
while(n>0):
    dig=n%10
    rev=rev*10+dig
    n=n//10
if(spare==rev):
    print("The number is a palindrome")
else:
    print("The number isn't a palindrome")

