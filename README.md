- 👋 Hi, I’m @SMHaari

#This program is finding prime number in while loop


def it_prime(n):
    if n<=1:
        return False
    if n<=3:
        return True
    if n % 2==0 or n % 3==0:
        return False
    i=5
    while i * i <= n:
        if n % i == 0 or n %(i + 2)==0:
            return False
        i+=6
        return True


number = int (input("enter the number: "))

if it_prime(number):
    print(f"{number} is prime number.")
else:
     print(f"{number} is not prime number")





