<h2 align=center> <b>My-program-in-python-to-make-a-employee-table-which-give-your-salary-in-year-with-tax</b></h2>

<p> For better understanading check the **_Source Code_**

```
Name=input("Enter the name:")
Emp_Id=input("Enter the Emp_Id:")
Debth=input("Enter the Debth:")
Designation=input("Enter the Designation:")
print("Enter employee details:")
print('Name','Emp_Id','Debth','Designation')
print(Name,Emp_Id,Debth,Designation)
hw=int(input("Enter the Worked hour:"))
ph=int(input("Pay Per hour:"))
wm=int(input("No of weak in a month:"))
def pay(hw):
    count=0
    if(hw>40):
        hw=count+ph
        print(hw)
    else:
        hw=ph-count
        print(hw)
        return hw
print(hw)
pay= (hw)*(ph)*(wm)
print("montly salary tax")
if(pay<40000):
    print("no tax")
elif(40000<pay<50000):
    tax=(pay*10)/100
    print(tax)
    print('10 % tax')
else:
    tax=(pay*20)/100
    print(tax)
    print("20% tax")
print("annual salary")
annual=0
for i in range(1,12):
    if(i==0):
        print(pay)
    else:
        annual=annual+pay
        print(annual)
print("annual salry after paying tax are given below")
n=int(input("Enter no of month"))
def annual(tax):
    annual=annual*n
    if(0<annual<500000):
        print("no tax")
    elif(500000<annual<1000000):
        tax=(annual*10)/100
        print("10% tax on annual income")
    else:
        tax=(annual*20)/100
        print(tax)
        return tax
print(tax)
```

<h3 align=center><b>Thank You</b></h3>
