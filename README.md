
#zadanie 2
#sprawdż czy liczba jest odd czy even i wyświetl poprawny komunikat

number = int(input('Give me your number: '))

if number%2 == 0 and number%4 !=0:
    print('You chose',number,'this is odd number')
elif number%4 == 0:
    print('You chose',number,'this number can be divided by 4')
else:
    print('You chose',number,'this is even number')

#zadanie 2A
#check to divide by
print('Now i will ask you to give me two numbers...')
num = int(input('Give me the first number: '))
check = int(input('Give me the second number: '))
print("Now let's check what we can do")
            
if num % check == 0:
    print('You can divide',num,'by',check,'and the result is',int(num/check))
else:
    print("Sorry, you can't divide",num,"by",check)
    
    
#zadanie 4
# zapytaj użytkownika o liczbę
#wyświetl wszystkie liczby, które są dzielnikami liczba podanej przez użytkownika

number = (int(input('Give me your number: ')))

for i in range(1,number+1):
    if number%i==0:
        print('Your number is',number,'You can divide it by',i,'and the result is',\
          int(number/i))

