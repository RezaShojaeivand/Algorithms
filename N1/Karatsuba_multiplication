
# Karatsuba Multiplication

def karatsubaMul(x,y) :
    n = len(x)
    m = len(y)
    if (n%2 == 0 and n == m):
        print('Numbers length are Even, The answer is:\n')
        while (n != 1) :
            if (n%2 == 0) :
                n = n/2
                if n == 1 :
                    licKara = True
            else :
                break

        if (n == 1) :
            print( int(x) * int(y))
        elif (licKara is True) :
            a = int(x[0:(len(x)/2)])
            b = int(x[(len(x)/2):])
            c = int(y[0:(len(y)/2)])
            d = int(y[(len(y)/2):])
            print( ((10**n)*a*c) + ((10**(n/2))*(a*d + b*c)) + b*d)
        else :
            print('Numbers length are not acceptable')
    elif (n != m) :
        print('Numbers length are not idnetical')
    elif (n %2 != 0) :
        print('Numbers length are Odd')
        
Num1 = input('Enter First Number: ')
Num2 = input('Enter Second Number: ')

karatsubaMul(Num1,Num2)
