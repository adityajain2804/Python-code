# Python-code
"Temperature Cnoverter "

temp = float(input("Enter the temperature :"))
temp_type = input("Enter the type of temperature 'C' or 'F' : ")
C = (temp-32)*5/9
F= temp*9/5  +32
if temp_type == 'C':
    print(C)
elif temp_type == 'F':
    print(F)
else:
    print("Input is wrong")
    
