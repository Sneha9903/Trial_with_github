# Trial_with_github
1styear
# Given a positive integer (n), return a list containing the first n integers in the Fibonacci series

def fibo(n):
  lis=[0,1]
  for i in range(2,n):
    a=lis[i-2]+lis[i-1]
    lis.append(a)
  print(lis)
