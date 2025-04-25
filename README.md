# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the required libraries numpy and sys.
  
2. Input the size of the matrix n and define augmented matrix a as a NumPy array of size (n, n+1). Initialize the solution array x as a NumPy array of size n.
   
3. Perform forward elimination to transform the augmented matrix into an upper triangular form:

   For each pivot row, ensure the pivot element is non-zero.


   Subtract multiples of the pivot row from the rows below to eliminate the elements below the pivot.

4. Perform backward substitution to compute the solution:
   

   Start with the last variable and substitute back into the equations to find the remaining variables.

5. Display the solution values of all variables using formatted output.


 6.Verify the results for correctness.

## Program:
```
/*
Program to find the solution of a matrix using Gaussian Elimination.
Developed by: PRIYADARSHINI K
RegisterNumber: 212224100046
*/
```
![image](https://github.com/user-attachments/assets/88efbfaa-d930-4f70-bef5-fb0ff4dc4d17)


## Output:
![image](https://github.com/user-attachments/assets/8989d012-4a39-4b68-9caf-33cff36ad3d4)



## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

