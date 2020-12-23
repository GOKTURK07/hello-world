# hello-world
Just another repository


x1=input("lütfen 1.veriyi giriniz:")
x2=input("lütfen 2.veriyi giriniz:")
x3=input("lütfen 3.veriyi giriniz:")
x4=input("lütfen 4.veriyi giriniz:")
x5=input("lütfen 5.veriyi giriniz:")

print("\n")
try:
    val1 = int(x1)
    print(f'Value1 =  {val1}',type(val1))
except ValueError:
    try:
        val1 = float(x1)
        print(" Value1 = ", type(val1))
    except ValueError:
        val1=x1
        print("Value1",type(val1))
              
print("\n")
try:
    val2 = int(x2)
    print(f'Value2 =  {val2}',type(val2))
except ValueError:
    try:
        val2 = float(x2)
        print(" Value2 = ", type(val2))
    except ValueError:
        val2=x2
        print("Value2",type(val2))

print("\n")
try:
    val3 = int(x3)
    print(f'Value3 =  {val3}',type(val3))
except ValueError:
    try:
        val3 = float(x3)
        print(" Value3 = ", type(val3))
    except ValueError:
        val3=x3
        print("Value3",type(val3))
        
print("\n")
try:
    val4 = int(x4)
    print(f'Value4 =  {val4}',type(val4))
except ValueError:
    try:
        val4 = float(x4)
        print(" Value4 = ", type(val4))
    except ValueError:
        val4=x4
        print("Value4",type(val4))
        
print("\n")
try:
    val5 = int(x5)
    print(f'Value5 =  {val5}',type(val5))
except ValueError:
    try:
        val5 = float(x5)
        print(" Value4 = ", type(val5))
    except ValueError:
        val4=x5
        print("Value5",type(val5))
