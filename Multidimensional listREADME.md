python/README.md

emp= []
for i in range(1,5):
    l_1=[]
    for j in range (1,4):
        ui=input('enter value:')
        l_1.append(ui)
    print()
    emp.append(l_1)
print(emp)

**#another method**
emp=[]
for i in range(5):
    s=input(f'enter your seq {i+1}:')
    d=input(f'enter your name {s}:')
    p=input(f'enter your profile{s}:')
    emp.append((s,d,p))
print(emp)

**#another method**
emp=[]
for i in range(3):
    s=input('enter data of employee with space:').split()
    emp.append(s)
print(emp)
