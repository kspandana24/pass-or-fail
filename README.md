# pass-or-fail#pass or fail
sno=int(input('enter student no:'))
sname=input("enter student name:")
sgroup=input('enter student group:')
s1=int(input("maths marks:"))
s2=int(input("physics marks:"))
s3=int(input("computer marks:"))
s4=int(input("hindi marks:"))
s5=int(input("english marks:"))
s6=int(input("online business:"))
if s1>=35 and s2>=35 and s3>=35 and s4>=35 and s5>=35 and s6>=35:
    print('pass')
else:
    print('fail')
