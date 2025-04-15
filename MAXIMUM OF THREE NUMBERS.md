# Experiment No: 5 – Finding the Largest Among Three Numbers

## AIM  
To write a Python program to find the largest among three numbers using conditional expression (ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare the numbers to find the largest:  
   - If `num1` is greater than or equal to both `num2` and `num3`, then `num1` is the largest.  
   - Else if `num2` is greater than or equal to both `num1` and `num3`, then `num2` is the largest.  
   - Otherwise, `num3` is the largest.  
4. Print the largest value in the format:  
   `"The largest of num1, num2, num3 is max_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-
# Name-
# Write your code here

num1 = int(input())
num2 = int(input())
num3 = int(input())

max_num = num1 if (num1 >= num2 and num1 >= num3) else num2 if (num2 >= num1 and num2 >= num3) else num3

print(f"The largest of {num1}, {num2}, {num3} is {max_num}")

```

## OUTPUT

## RESULT


