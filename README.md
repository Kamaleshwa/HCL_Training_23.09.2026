# HCL_Training_23.09.2026

### Name : KAMALESHWAR KV
### Reg no : 212223240063
### HCL_Python_Sample_Code_23-09-2026
## Code 1 :
Write a Python program which accepts a sequence of comma separated 4 digit binary numbers as its input and then check whether they are divisible by 5 or not. The numbers that are divisible by 5 are to be printed in a comma separated sequence. Example: 0100,0011,1010,1001 Then the output should be: 1010

```
a = input().split(",")
r=[]
for x in a:
  if int(x,2)%5==0:
    r.append(x)
print(",".join(r))
```
## Output:
<img width="1399" height="373" alt="image" src="https://github.com/user-attachments/assets/40f967ba-200e-4941-b55a-bde0449b850b" />

## Code 2 :
Write a Python program that accepts a sentence and calculate the number of letters and digits. Suppose the following input is supplied to the program: hello world! 123 Then, the output should be: LETTERS 10 DIGITS 3

```
s=input()
letter=0
digit=0

for c in s:
  if c.isalpha():
    letter+=1
  elif c.isdigit():
    digit+=1
print("LETTER :",letter)
print("DIGIT :",digit)
```

## Output:
<img width="1389" height="419" alt="image" src="https://github.com/user-attachments/assets/a0facad3-281a-4af6-9be9-fb50f312d1ea" />


## Code 3 :
Write a program which can compute the factorial of a given numbers.The results should be printed in a comma-separated sequence on a single line.Suppose the following input is supplied to the program:8 Then, the output should be:40320

```
n=int(input())
fact=1
for i in range(1,n+1):
  fact*=i
print(",".join(str(fact)))
```
## Output:
<img width="1379" height="395" alt="image" src="https://github.com/user-attachments/assets/35c080b2-f40b-4f6b-b30e-e29c1c47f730" />

