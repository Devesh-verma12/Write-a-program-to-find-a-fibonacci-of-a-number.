# Write-a-program-to-find-a-fibonacci-of-a-number.

nterms = int(input("How many terms? "))
# 7
n1, n2 = 0, 1
count = 0

if nterms <= 0:
   print("Please enter a positive integer")
elif nterms == 1:
   print("Fibonacci sequence upto",nterms,":")
   print(n1)
else:
   print("Fibonacci sequence:")
   while count < nterms:
       print(n1)
       nth = n1 + n2
       n1 = n2
       n2 = nth
       count += 1
# Fibonacci sequence:
# 0
# 1
# 1
# 2
# 3
# 5
# 8
