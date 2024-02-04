def sum(n):
  


  return n * (n + 1) // 2


n = int(input("Enter your number: "))


if n <= 0:
  print("enter a positive integer:")
else:
  
  sum = sum(n)
  print(sum)
