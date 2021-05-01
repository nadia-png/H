num1= float(input ("enter number:"))
oper= input("enter operator:")
num2=float(input ("enter number:"))
 
if oper== "+":
	   print(num1+num2)
	   print =(num1,oper,num2,"=",num1+num2)

elif oper=="/":
 try:
       print (num1/num2)
       print=(num1,oper,num2,"=",num1/num2)
 except ZeroDivisionError :
       print ("zero cannot divide")
       
elif oper=="*":
       print(num1*num2)
       print=(num1,oper,num2,"=",num1*num2)
elif oper=="-":
        print(num1-num2)
        print=(num1,oper,num2,"=",num1-num2)
