# scientific-calculator
#BYREDDY AKHILESWAR REDDY Scientific calculator of 100 functions
print ('BYREDDY AKHILESWAR REDDY 21BCE9783 SCICALC')
import math 
import cmath 
import numpy as np 
print(""" 
press -  
1 - Addition(x, y) 
2 - subtraction(x,y) 
3-multiplication(x,y) 
4 - division(x, y) 
5- exponent(x, y) 
6 - power of 2 nos
7 - reciprocal of no
8 - nth term of AP
9 - factorial(x) 
10 - log(x) 
11 - sin(x)
12 - cos(x)
13 - tan(x)
14 - cot(x)
15 - sec(x) 
16 - cosec(x) 
17 - sinh(x)
18 - cosh(x)
19 - tanh(x)
20 - coth(x)
21 - arcsin(x) 
22 - arccos(x)
23 - arctan(x)
24 - arccosec(x)
25 - arcsec(x)
26 - arccot(x)
27 - e^x
28 - log10(x) 
29 - bin2hexa
30 - ln(x) 
31 - matrix addition 3x3
32 - matrix substraction 3x3
33 - transpose 
34 - matrix multiplication
35 - sum of n natural numbers 
36 - solving quadratic
37 - determinant 
38 - UNION OF SET
39 - INTERSECTION OF SET
40 - SIMPLE INTEREST 
41 - COMPOUND INTErest
42 - LCM
43 - HCF 
44 - SQUARE ROOT 
45 - FLOOR AND CEIL 
46 - REMAINDER 
47 - CUMSUM
48 - CUMPRODUCT
49 - DEG2RAD
50 - RAD2DEG
51 - INNER PROD
52 - DOT PRODUCT
53 - TRACE OF MATRIX
54 - RANK OF MATRIX 
55 - TRUE INVERSE
56 - PSEUDO INV
57 - FLATTEN
58 - SOLVING LINEAR EQUATIONS IN THREE VARIABLES
59 - SUM O TERMS OF AP
60 - NTH TERM OF GP
61 - SUM OF N TERMS OF GP 
62 - PRODUCT OF N TERMS OF GP
63 - DEC 2 BIN
64 - DEC 2 OCT
65 - DEC 2 HEXA
67 - BIN 2 DEC
66 - BIN 2 OCTA
68 - HEXA 2 DEC
69 - HEXA 2 BIN
70 - HEXA 2 OCTA
71 - OCTA 2 DEC
72 - OCTA 2 BIN 
73 - OCTA 2 HEXA
74 - MEAN
75 - CALCULATE THE GST 
76 - SOLVING LINEAR EQUATIONS IN TWO VARIABLES


""") 
o = input("") 
if o == "1": 
    x = int(input("1st number -")) 
    y = int(input("2nd number -")) 
    print(x + y)

elif o == "2": 
    x = int(input()) 
    y = int(input()) 
    print(x-y) 

elif o == "3": 
    x = int(input()) 
    y = int(input()) 
    print(x*y) 

elif o == "4": 
    x = int(input()) 
    y = int(input()) 
    print(x/y) 

elif o == "5": 
    x = int(input()) 
    y = int(input()) 
    print(x**y)

elif o == "6": 
    x = int(input()) 
    y = int(input()) 
    print(x**y) 

elif o == "7": 
    x=int(input("enter no for the reciprocal ")) 
    print(1/x)

elif o == "8":
    a=int(input('enter first term '))
    n=int(input("enter no of term"))
    c=int(input('enter difference')) 
    tn=a+(n-1)*c 
    print(tn)

elif o == "9": 
    x = int(input()) 
    print(math.factorial(x)) 

elif o == "10": 
    x = int(input()) 
    print(math.log(x))

#trigno functions

elif o == "11":
    n=int(input(" get  of angle ="))
    x = np.sin(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

elif o == "12": 
    n=int(input(" get  of angle ="))
    x = np.cos(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

elif o == "13":
    n=int(input(" get  of angle ="))
    x = np.tan(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

elif o == "14": 
    n=int(input(" get  of angle ="))
    x = np.cot(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

elif o == "15": 
    n=int(input(" get  of angle ="))
    x = np.sec(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

elif o == "16": 
    n=int(input(" get  of angle ="))
    x = np.cosec(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

#hyptrig func 

elif o == "17": 
    n=int(input(" get  of angle ="))
    x = np.sinh(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad) 

elif o == "18": 
    n=int(input(" get  of angle ="))
    x = np.cosh(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

elif o == "19":
    n=int(input(" get  of angle ="))
    x = np.tanh(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

elif o == "20": 
    n=int(input(" get  of angle ="))
    x = np.coth(np.n)
    rad = np.deg2rad(x)
    print(x," ",rad)

#invtrig func     

elif o == "21": 
    n=int(input("value to get trig inverse ="))
    x = np.arcsin(n)
    print(x) 

elif o == "22": 
    n=int(input("value to get trig inverse ="))
    x = np.arccos(n)
    print(x)  

elif o == "23": 
    n=int(input("value to get trig inverse ="))
    x = np.arctan(n)
    print(x)  

elif o == "24": 
    n=int(input("value to get trig inverse ="))
    x = np.arccosec(n)
    print(x)  

elif o == "25": 
    n=int(input("value to get trig inverse ="))
    x = np.arcsec(n)
    print(x) 

elif o == "26": 
    n=int(input("value to get trig inverse ="))
    x = np.arccot(n)
    print(x)  

elif o == "27": 
    x = int(input()) 
    print(math.exp(x)) 

elif o == "28": 
    x=int(input("enter power of log"))
    out=np.log10(x)
    print(out)

elif o == "29":
    binary_string = input('enter bin')
    decimal_representation = int(binary_string, 2)
    hexadecimal_string = hex(decimal_representation)
    print(hexadecimal_string)

elif o == "30": 
    x = int(input()) 
    print(np.log(x))

#matrix

elif o == "31":
    matOne = []
    print("Enter 9 Elements for First Matrix: ")
    for i in range(3):
        matOne.append([])
        for j in range(3):
            num = int(input())
            matOne[i].append(num)
    matTwo = []
    print("Enter 9 Elements for Second Matrix: ")
    for i in range(3):
        matTwo.append([])
        for j in range(3):
            num = int(input())
            matTwo[i].append(num)

    matThree = []
    for i in range(3):
        matThree.append([])
        for j in range(3):
            matThree[i].append(matOne[i][j]+matTwo[i][j])

    print("\nAddition Result of Two Given Matrix is:")
    for i in range(3):
        for j in range(3):
            print(matThree[i][j], end=" ")
    print()
 
elif o == "32":
    matOne = []
    print("Enter 9 Elements for First Matrix: ")
    for i in range(3):
        matOne.append([])
        for j in range(3):
            num = int(input())
            matOne[i].append(num)
    matTwo = []
    print("Enter 9 Elements for Second Matrix: ")
    for i in range(3):
        matTwo.append([])
        for j in range(3):
            num = int(input())
            matTwo[i].append(num)

    matThree = []
    for i in range(3):
        matThree.append([])
        for j in range(3):
            matThree[i].append(matOne[i][j]-matTwo[i][j])

    print("\nsubstraction Result of Two Given Matrix is:")
    for i in range(3):
        for j in range(3):
            print(matThree[i][j], end=" ")
    print() 

elif o == "33":
    R = int(input("Enter the number of rows:"))
    C = int(input("Enter the number of columns:"))
    print("Enter the entries in a single line (separated by space): ")
    entries = list(map(int, input().split()))
    matrix = np.array(entries).reshape(R, C)
    print(matrix)
 
elif o == "34": 
    A=[]
    n=int(input("Enter N for N x N matrix: "))         
    print("Enter the element ::>")
    for i in range(n):
        row=[]
        for j in range(n):
            row.append(int(input()))
            A.append(row)    
    print(A)
    print("Display Array In Matrix Form")
    for i in range(n):
        for j in range(n):
            print(A[i][j], end=" ")
    print()
    B=[]
    n=int(input("Enter N for N x N matrix : "))
    print("Enter the element ::>")
    for i in range (n):
        row=[]
        for j in range(n):
            row.append(int(input()))
            B.append(row)
    print(B)
    print("Display Array In Matrix Form")
    for i in range(n):
        for j in range(n):
            print(B[i][j], end=" ")
    print()                                           
    result = [[0,0,0], [0,0,0], [0,0,0]] 
    for i in range(len(A)):
        for j in range(len(B[0])):
            for k in range(len(B)):
                result[i][j] += A[i][k] * B[k][j] 
    print("The Resultant Matrix Is ::>")
    for r in result:
        print(r)

elif o == "35":
    n=int(input("enter no "))
    sum=n*(n+1)/2
    print(sum)

elif o == "36":
    a = float(input("a"))
    b = float(input('b'))
    c = float(input('c'))
    d = (b**2) - (4*a*c)
    sol1 = (-b-cmath.sqrt(d))/(2*a)
    sol2 = (-b+cmath.sqrt(d))/(2*a)
    print('The solution are {0} and {1}'.format(sol1,sol2))

elif o == "37":
    a=int(input('enter'))
    b=int(input('enter'))
    c=int(input('enter'))
    d=int(input('enter'))
    e=int(input('enter'))
    f=int(input('enter'))
    g=int(input('enter'))
    h=int(input('enter'))
    i=int(input('enter'))
    r1=[a,b,c]
    r2=[d,e,f]
    r3=[g,h,i]
    n_array = np.array([r1,r2,r3])
    print("Numpy Matrix is:")
    print(n_array)
    det = np.linalg.det(n_array)
    print("\nDeterminant of given 3x3 matrix:")
    print(int(det))

elif o == "38":
    set1={}
    lst=list(set1)
    n = int(input("Enter number of elements : "))
    for i in range(0, n):
        ele = int(input())
        lst.append(ele)
    set1=set(lst)     
    print(set1)

    set2={}
    lst=list(set2)
    n = int(input("Enter number of elements : "))
    for i in range(0, n):
        ele = int(input())
        lst.append(ele)
    set2=set(lst)     
    print(set2)

    print(set1.union(set2))

elif o == "39":
    set1={}
    lst=list(set1)
    n = int(input("Enter number of elements : "))
    for i in range(0, n):
        ele = int(input())
        lst.append(ele)
    set1=set(lst)     
    print(set1)

    set2={}
    lst=list(set2)
    n = int(input("Enter number of elements : "))
    for i in range(0, n):
        ele = int(input())
        lst.append(ele)
    set2=set(lst)     
    print(set2)

    print(set1.intersection(set2))


elif o == "40":
    p=float(input("principal amount"))
    t=float(input("time ="))
    r = float(input("rate of intererst"))
    SI = p*t*r/100
    print(SI,'simple interest')

elif o == "41":
    p=float(input('principal amount '))
    r=float(input('rate'))
    n = float(input("no of time s applied per time period "))
    t=float(input("time"))
    CI=p*(1+r/n)**(n*t)
    print(CI)

elif o == "42":
    arr = []
    n = int(input("no of element for what do u want lcm "))
    for i in range(0,n):
        ele = int(input('enter nos'))
        arr.append(ele)
        print(arr)
    A=np.array(arr)
    lcm=np.lcm.reduce(A)
    print(lcm)    

elif o == "43":
    arr = []
    n = int(input("no of element for what do u want gcd "))
    for i in range(0,n):
        ele = int(input('enter nos'))
        arr.append(ele)
        print(arr)
    A=np.array(arr)
    gcd=np.gcd.reduce(A)
    print(gcd) 

elif o == "44":
    x=float(input('no that u want square root'))
    y=x**0.5
    print(y)

elif o == "45":
    x=float(input('enter the digit with decimals '))
    y=math.floor(x)
    z=math.ceil(x)
    print("floor",  y ,"ceil", z ) 

elif o == "46":
    x=float(input("enter no that u want remainder"))
    y=float(input("enter divisor"))
    rem=x%y
    print(rem)

elif o == "47":
    arr = []
    n = int(input("no of element for what do u want cumsum "))
    for i in range(0,n):
        ele = int(input('enter nos'))
        arr.append(ele)
        print(arr)
    A=np.array(arr)
    cumsum=np.cumsum(A)
    print(cumsum[-1])     

elif o == "48":
    arr = []
    n = int(input("no of element for what do u want prod "))
    for i in range(0,n):
        ele = int(input('enter nos'))
        arr.append(ele)
        print(arr)
    A=np.array(arr)
    prod=np.prod(A)
    print(prod)
     
elif o == "49":
    deg = float(input("enter  in deg"))
    rad = np.deg2rad(deg)
    print(rad)

elif o == "50":
    rad = float(input("enter  in radians"))
    deg = np.rad2deg(rad)
    print(deg)

elif o == "51":
    n=int(input('enter the size'))
    a=[]
    b=[]
    for i in range(0,n):
        ele1=int(input("enter the element of 1st vector "))
        a.append(ele1)
    for j in range(0,n):
        ele2=int(input("enter the element of 2nd vector "))
        b.append(ele2)
    print(a)    
    print(b)
    print(np.inner(a,b))

elif o == "52":
    r=int(input('no of rows for mat1'))
    c=int(input('no of cols for mat1'))
    mat1=[[int(input()) for x in range(c)] for y in range(r)]
    print("mat1",mat1)
    r=int(input('no of rows for mat2'))
    c=int(input('no of cols for mat2'))
    mat2=[[int(input()) for x in range(c)] for y in range(r)]
    print("mat2",mat2)
    print(np.dot(mat1,mat2))

elif o == "53":
    r=int(input('no of rows for mat1'))
    c=int(input('no of cols for mat1'))
    mat1=[[int(input()) for x in range(c)] for y in range(r)]
    print("mat1",mat1)
    x=0
    for i in range(len(mat1)):
        for j in range(len(mat1)):
            if i==j:
                x+=mat1[i][j]
    print('trace', x)

elif o == "54":
    r=int(input('no of rows for mat1'))
    c=int(input('no of cols for mat1'))
    mat1=[[int(input()) for x in range(c)] for y in range(r)]
    print("mat1",mat1)
    rank = np.linalg.matrix_rank(mat1)
    print('rank', rank)

elif o == "55":
    r=int(input('no of rows for mat1'))
    c=int(input('no of cols for mat1'))
    mat1=[[int(input()) for x in range(c)] for y in range(r)]
    print("mat1",mat1)
    a=np.linalg.det(mat1)
    print('\ndeterminant',np.round(a))
    inv=np.linalg.inv(mat1)
    print('inv of mat1 is',inv)

elif o == "56":
    r=int(input('no of rows for mat1'))
    c=int(input('no of cols for mat1'))
    mat1=[[int(input()) for x in range(c)] for y in range(r)]
    print("mat1",mat1)
    a=np.linalg.det(mat1)
    print('\ndeterminant',np.round(a))
    inv=np.linalg.pinv(mat1)
    print('inv of mat1 is',inv)

elif o == "57":
    r=int(input('no of rows for mat1'))
    c=int(input('no of cols for mat1'))
    mat1=[[int(input()) for x in range(c)] for y in range(r)]
    print("mat1",mat1)
    a=np.array(mat1)
    print(a.flatten())

elif o == "58":
    a1=float(input('enter x coeff of eq 1='))
    b1=float(input('enter y coeff of eq 1='))
    c1=float(input('enter z coeff of eq 1='))
    a2=float(input('enter x coeff of eq 2='))
    b2=float(input('enter y coeff of eq 2='))
    c2=float(input('enter z coeff of eq 2='))
    a3=float(input('enter x coeff of eq 3='))
    b3=float(input('enter y coeff of eq 3='))
    c3=float(input('enter z coeff of eq 3='))
    
    D1=float(input('enter const coeff of eq 1='))
    D2=float(input('enter const coeff of eq 2='))
    D3=float(input('enter const coeff of eq 3='))
    a = np.array([[a1,b1,c1],[a2,b2,c2],[a3,b3,c3]])
    b = np.array([[D1],[D2],[D3]])
    x = np.linalg.solve(a, b)
    print(x)

elif o == "59":
    a=float(input('enter first term of a ap'))
    n=int(input('up to which term to u want sum of a ap'))
    d=float(input('common difference of ap'))
    sumofn=(n/2)*(2*a+(n-1)*d)
    print("sum of n terms of ap",sumofn)

elif o == "60":
    a=float(input('enter first term of a gp'))
    n=int(input('which term do u of a gp'))
    r=float(input('common rATIO of GP'))
    nthgp=a*(r**(n-1))
    print("nth terms of gp",nthgp)

elif o == "61":
    a=float(input('enter first term of a gp'))
    n=int(input('which term do u wamt sum of a gp'))
    r=float(input('common ratio of GP'))
    t=(a*((r**n)-1))/(r-1)
    print("nth terms of gp",t)

elif o == "62":
    a=float(input('enter first term of a gp'))
    n=int(input('which term do u wamt product of a gp'))
    r=float(input('common ratio of GP'))
    ntt=a*(r**(n-1)) 
    t=(a*(ntt**n))**0.5
    print("nth product of gp",t)

elif o == "63":
    number = int(input("Enter any decimal number: "))
    print("Equivalent Binary Number: ", bin(number))

elif o == "64":
    number = int(input("Enter any decimal number: "))
    print("Equivalent 0cta Number: ", oct(number))

elif o == "65":
    number = int(input("Enter any decimal number: "))
    print("Equivalent hexa Number: ", hex(number))

elif o == "66":
    def convert(num):
        octalDigit = 0
        count = 1
        i = 0
        pos = 0
        octalArray = [0] * 32
        while num != 0:
            digit = num % 10
            octalDigit += digit * pow(2, i)
            i += 1
            num //= 10
            octalArray[pos] = octalDigit
            if count % 3 == 0:
                octalDigit = 0
                i = 0
                pos += 1
                count += 1
        for j in range(pos, -1, -1):
            print(octalArray[j], end='')


    binary = int(input("bin no"))
    convert(binary)

elif o == "67":
    num = int(input('enter binary'))
    binary_val = num
    decimal_val = 0
    base = 1
    while num > 0:
        rem = num % 10
        decimal_val = decimal_val + rem * base
        num = num // 10
        base = base * 2
    print("Binary Number is {}\nDecimal Number is {}".format(binary_val, decimal_val))

elif o == "68":
    hex = input("enter hexa no")
    dec = int(hex, 16)
    print('Value in hexadecimal:', hex)
    print('Value in decimal:', dec)

elif o == "69":
    hex = input("enter hexa no")
    bin = bin(hex, 16)
    print('Value in hexadecimal:', hex)
    print('Value in biniary:', bin)

elif o == "70":
    import math
    hex=input("Enter Hexadecimal Number:")
    value=0
    decimal=0
    j=len(hex)
    j-=1
    for i in range(0,len(hex)):
        if hex[i]>='0' and hex[i]<='9' :
            value=(int)(hex[i])
        if hex[i]=='A' or hex[i]=='a':
            value=10
        if hex[i] == 'B' or hex[i] == 'b':
            value=11
        if hex[i] == 'C' or hex[i] == 'c':
            value=12
        if hex[i] == 'D' or hex[i] == 'd':
            value=13
        if hex[i] == 'E' or hex[i] == 'e':
            value=14
        if hex[i] == 'F' or hex[i] == 'f':
            value=15
        decimal=decimal+(int)(value*math.pow(16,j))
        j-=1
    sem=1
    octal=0
    while(decimal !=0):
        octal=octal+(decimal%8)*sem
        decimal=decimal//8
        sem=int(sem*10)
    print("Octal Number is:",octal)

elif o == "71":
    def octalToDecimal(n):
        num = n
        dec_value = 0
        base = 1
        temp = num
        while (temp):
            last_digit = temp % 10
            temp = int(temp / 10)
            dec_value += last_digit * base
            base = base * 8
        return dec_value
    num = int(input("octal no"))
    print(octalToDecimal(num))

elif o == "72":
    print("Enter octal number: ")
    octal=int(input())
    decimal = 0
    i = 0
    binary = 0
    while (octal != 0):
        decimal = decimal + (octal % 10) * pow (8, i)
        i+=1
        octal = octal // 10
    i = 1
    while (decimal != 0):
        binary = binary + (decimal % 2) * i
        decimal = decimal // 2
        i = i * 10
    print ("Binary number is: ", binary)

elif o == "73":
    i=0
    octal=int(input("Enter Octal number:"))
    Hex=['0']*50
    decimal = 0
    sem = 0
    while octal!=0:
        decimal=decimal+(octal%10)*pow(8,sem)
        sem+=1
        octal=octal// 10
    while decimal!=0:
        rem=decimal%16
        if rem<10:
            Hex[i]=chr(rem+48)#48 Ascii=0
            i+=1
        else:
            Hex[i]=chr(rem+55) #55 Ascii=7
            i+=1
        decimal//=16
    print("Hexadecimal number is:")
    for j in range(i-1,-1,-1):
        print(Hex[j],end="")

elif o == "74":
    n=int(input("no of ele that u waant mean"))
    m=0
    mean=1
    for i in range(0,n):
        ele =int(input())
        m += ele
        mean=m/n
    print(mean)

elif o == "75":
    P=float(input("principal amount"))
    gstR=float(input("enter gst rate %"))
    gstamount=P*gstR/100
    T=P+gstamount
    print("final price including gst is",T)

elif o == "76":
    a1=float(input('enter x coeff of eq 1='))
    b1=float(input('enter y coeff of eq 1='))
    a2=float(input('enter x coeff of eq 2='))
    b2=float(input('enter y coeff of eq 2='))
    D1=float(input('enter const coeff of eq 1='))
    D2=float(input('enter const coeff of eq 2='))
    a = np.array([[a1,b1],[a2,b2]])
    b = np.array([[D1],[D2]])
    x = np.linalg.solve(a, b)
    print(x)

print(" ")
print(" ")
print(" ")
print("THE END ")
print(" THANK YOU  :) :) :) ")
