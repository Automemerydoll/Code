# Code
temp = input("C :")
degree = int(temp[:-1])
unit=temp[-1].upper()

if unit == "C":
    #result=(9*degree)/5+32
    result=degree*2.54/1
    unit_result="Fahrenheit"
if unit == "F":
    #result=(degree-32)*5/9
    result=degree*1/2.54
    unit_result="Cessius"
print("Tranfer --->",temp,"-->",unit_result,"=",result)
