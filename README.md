a = int(input(""))

if(a%100 == 0 and a%400 != 0):
    print("False")

elif(a%100 == 0 and a%400 == 0):
    print("True")

elif(a%4==0):
    print("True")

else:
    print("False")
