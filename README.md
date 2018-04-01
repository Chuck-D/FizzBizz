# FizzBuzz

for num in range(1,21):
  #get numbers evenly divisible by 3 and 5.  print FizzBuzz
  if num % 3 == 0 and num % 5 == 0:
    print("FizzBuzz")
  elif num % 3 == 0:
    print("Fizz")
  elif num % 5 == 0:
    print("Buzz")
  else:
    print(num)
