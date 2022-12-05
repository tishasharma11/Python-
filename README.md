# Python-
Made a Multiplication application table with the help of loop function
import math
print("\t\t\tMultiplication Tables\n")
n=int(input("Print tables till: "))
x=int(input("Print table multiplications till: "))
print("________________________________________________________________________________\n")
for i in range(2,n+1):
    print(i,end="\t")
print()
print("________________________________________________________________________________\n")
j=0
k=0
for j in range (2,x+1):
    for k in range(2,n+1):
        print(j*k,end="\t")
    print("\n")
