# EX-NO-6-Pseudo-Random-Number
## NAME: MOPURI SARADEEPIKA
## REG NO : 212224040201
## DATE : 17/09/2025
# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
import random
def main():
    n = int(input("Enter how many random numbers to generate: "))
    print("Generated Random Numbers:")
    for _ in range(n):
        print(random.randint(0, 2**31 - 1), end=" ")  # randint to mimic C's rand() range
if _name_ == "_main_":
    main()
```

# OUTPUT:
<img width="648" height="228" alt="Screenshot 2025-09-17 093356" src="https://github.com/user-attachments/assets/5d42bcd7-4347-42e9-9acd-bd4185a5988b" />

# RESULT:
The Implementation of Pseudorandom Number Generation Using Standard library is successful.
