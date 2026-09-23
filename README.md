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
<img width="1118" height="268" alt="image" src="https://github.com/user-attachments/assets/f48aa4fa-0aaa-4fbc-a01c-4a3318589afe" />

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
<img width="1125" height="305" alt="image" src="https://github.com/user-attachments/assets/bbb9dd38-9545-432d-93e3-107143fc82dd" />


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
<img width="1132" height="202" alt="image" src="https://github.com/user-attachments/assets/642d1dc5-b9d0-4d4b-aac7-6fc815c5c499" />

