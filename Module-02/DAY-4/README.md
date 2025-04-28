# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: VIJAY KUMAR B
RegisterNumber:  212222230173
*/
```

## Sourcecode.java:

```
import java.util.*;

public class SumOf2DArray {
    public static void main(String[] args) {
        Scanner v = new Scanner(System.in);
        int rows = v.nextInt();
        int cols = v.nextInt();

        int[][] array = new int[rows][cols];
        int sum = 0;

        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                array[i][j] = v.nextInt();
                sum += array[i][j];
            }
        }

        System.out.println("The sum of all values in the 2D array is: " + sum);
        v.close();
    }
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/b4ca4979-3054-4df9-bac2-956f56bf69c0)



## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.


