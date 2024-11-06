# PY-Practical-3
n = int(input("Enter the number of rows: "))

# Pyramid
for i in range(n):
    # Print leading spaces
    print(" " * (n - i - 1), end="")
    # Print stars with spaces
    print("* " * (i + 1))

# Reverse Pyramid
for i in range(n - 1, 0, -1):
    # Print leading spaces
    print(" " * (n - i), end="")
    # Print stars with spaces
    print("* " * i)



'''output
Enter the number of rows: 5
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
 * * * * 
  * * * 
   * * 
    * 
