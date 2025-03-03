# Right Angled Triangle Number Pattern

## Description
This Java program prints a right-angled triangle number pattern using nested loops. The pattern consists of numbers starting from 1 and increasing up to the current row number. This program demonstrates the use of nested loops, control flow, and systematic number printing.

## Pattern Output
When you run the program, the output will be:
```
1
12
123
1234
```

## Code Explanation
### Java Code
```java
package number_patterns;

public class RightAngledTriangle 
{
    public static void main(String[] args) 
    {
        for(int i=1; i<=4; i++) // Outer loop controls rows
        {
            for(int j=1; j<=i; j++) // Inner loop controls columns
            {
                System.out.print(j); // Prints numbers in a row
            }
            System.out.println(); // Moves to the next line after each row
        }
    }
}
```

### Explanation of Components

#### 1. **Outer for Loop** (`for(int i=1; i<=4; i++)`)
   - This loop runs from `i = 1` to `i = 4`, controlling the number of rows printed.
   - Each iteration represents a new row.

#### 2. **Inner for Loop** (`for(int j=1; j<=i; j++)`)
   - This loop runs from `j = 1` to `j = i`, printing numbers in each row.
   - The number of columns increases with each row, ensuring a triangle shape.

#### 3. **Printing Statements**
   - `System.out.print(j);`: Prints numbers without moving to the next line.
   - `System.out.println();`: Moves to the next line after printing each row.

## Key Concepts Used
- **Nested Loops**: Used to control row and column iteration.
- **Loop Conditions**: The inner loop depends on the outer loop variable to print numbers progressively.
- **System.out.print vs System.out.println**: Used to format the triangle correctly.

## Clone
```
git clone https://github.com/Ananthadatta02/Java-RightAngled_Triangle_Pattern.git
```
