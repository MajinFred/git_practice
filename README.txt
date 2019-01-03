Hello Git and GitHub

#function calling another function example
def max_num2(a,b):
  if (a>b):
    return a
  else:
    return b
  
def max_num(num1,num2,num3):
  return max_num2(max_num2(num1,num2),num3)
