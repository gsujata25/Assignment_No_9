# Assignment_No_9

1. Write a C++ program to define a structure named ‘Item‘ having members ‘id‘ (integer) and ‘cost‘ (float),
declare an array of 6 ‘Item‘ structures, initialize the first four elements with sample data, and then use a ‘for‘
loop to iterate through the entire array, displaying the details of any item whose ‘cost‘ is greater than 50.00.

Test Case 1:
Input:
Item items[6] = {
    {1, 45.75},  // Item 1
    {2, 60.50},  // Item 2
    {3, 120.00}, // Item 3
    {4, 35.30},  // Item 4
    {0, 0.0},    // Item 5 (not initialized)
    {0, 0.0}     // Item 6 (not initialized)
};

Output:
Item ID: 2, Cost: 60.5
Item ID: 3, Cost: 120

Test Case 2:
Item items[6] = {
    {1, 30.00},  // Item 1
    {2, 45.50},  // Item 2
    {3, 80.00},  // Item 3
    {4, 10.00},  // Item 4
    {0, 0.0},    // Item 5 (not initialized)
    {0, 0.0}     // Item 6 (not initialized)
};

Output:
Item ID: 3, Cost: 80


2. Write a C++ program to define a structure ‘Color‘ with members ‘red‘, ‘green‘, and ‘blue‘ (all integers),
declare and initialize an array of 5 ‘Color‘ structures with sample RGB values, and then use a ‘for‘ loop to
invert the color values of the first 3 elements in the array (by setting each component to 255−original value),
finally displaying the new RGB values for all 5 elements.

Test Case 1:
Input:
Color colors[5] = {
    {100, 150, 200}, // Color 1
    {255, 100, 50},  // Color 2
    {0, 0, 0},       // Color 3
    {128, 128, 128}, // Color 4
    {255, 255, 255}  // Color 5
};

Output:
Color 1: Red = 155, Green = 105, Blue = 55
Color 2: Red = 0, Green = 155, Blue = 205
Color 3: Red = 255, Green = 255, Blue = 255
Color 4: Red = 128, Green = 128, Blue = 128
Color 5: Red = 255, Green = 255, Blue = 255

Test Case 2:
Input:
Color colors[5] = {
    {200, 100, 50},  // Color 1
    {255, 0, 0},     // Color 2
    {10, 20, 30},    // Color 3
    {80, 90, 100},   // Color 4
    {200, 200, 200}  // Color 5
};

Output:
Color 1: Red = 55, Green = 155, Blue = 205
Color 2: Red = 0, Green = 255, Blue = 255
Color 3: Red = 245, Green = 235, Blue = 225
Color 4: Red = 175, Green = 165, Blue = 155
Color 5: Red = 200, Green = 200, Blue = 200

3. Write a C++ program to define a structure ‘Point‘ with members ‘x‘ and ‘y‘ (both floats), declare an array
of 7 ‘Point‘ structures, use a ‘for‘ loop to read the x and y coordinates for all 7 points from user input,
and then iterate through the array again to count and display how many of the entered points lie in the first
quadrant (where both x>0 and y>0).

Test Case 1:
Input:
Enter coordinates for 7 points (x, y):
Point 1 - x: 1.2
Point 1 - y: 3.4
Point 2 - x: -1.2
Point 2 - y: 3.4
Point 3 - x: 2.5
Point 3 - y: -4.6
Point 4 - x: 3.1
Point 4 - y: 2.3
Point 5 - x: -0.5
Point 5 - y: -1.2
Point 6 - x: 4.0
Point 6 - y: 5.1
Point 7 - x: -2.0
Point 7 - y: 2.0

Output:
Number of points in the first quadrant: 3

Test Case 2:
Input:
Enter coordinates for 7 points (x, y):
Point 1 - x: -3.0
Point 1 - y: 4.5
Point 2 - x: 2.0
Point 2 - y: -1.0
Point 3 - x: 5.0
Point 3 - y: 6.0
Point 4 - x: -1.5
Point 4 - y: -2.0
Point 5 - x: 0.0
Point 5 - y: 0.0
Point 6 - x: 7.0
Point 6 - y: 3.0
Point 7 - x: 4.5
Point 7 - y: -3.5

Output:
Number of points in the first quadrant: 2

4. Write a C++ program to define a structure ‘SalesRecord‘ with members ‘month‘ (string) and ‘amount‘ (float),
declare an array of 12 ‘SalesRecord‘ structures (representing a year), use a ‘for‘ loop to accept user input for
the ‘month‘ name and the ‘amount‘ for all 12 months, and then, using a single pass with a ‘for‘ loop, find and
display the ‘month‘ with the maximum sales ‘amount‘ and the ‘month‘ with the minimum sales ‘amount‘.

Test Case 1:
Input:
Enter sales data for each month:
Month 1:
Month Name: January
Sales Amount: 12000
Month 2:
Month Name: February
Sales Amount: 9500
Month 3:
Month Name: March
Sales Amount: 16000
Month 4:
Month Name: April
Sales Amount: 8000
Month 5:
Month Name: May
Sales Amount: 14000
Month 6:
Month Name: June
Sales Amount: 11000
Month 7:
Month Name: July
Sales Amount: 10000
Month 8:
Month Name: August
Sales Amount: 11500
Month 9:
Month Name: September
Sales Amount: 13000
Month 10:
Month Name: October
Sales Amount: 12500
Month 11:
Month Name: November
Sales Amount: 13500
Month 12:
Month Name: December
Sales Amount: 15500

Output:
Month with maximum sales: December with amount 15500
Month with minimum sales: April with amount 8000

Test Case 2:
Input:
Enter sales data for each month:
Month 1:
Month Name: January
Sales Amount: 4500
Month 2:
Month Name: February
Sales Amount: 5200
Month 3:
Month Name: March
Sales Amount: 5100
Month 4:
Month Name: April
Sales Amount: 4900
Month 5:
Month Name: May
Sales Amount: 5300
Month 6:
Month Name: June
Sales Amount: 5700
Month 7:
Month Name: July
Sales Amount: 5500
Month 8:
Month Name: August
Sales Amount: 4800
Month 9:
Month Name: September
Sales Amount: 5100
Month 10:
Month Name: October
Sales Amount: 5300
Month 11:
Month Name: November
Sales Amount: 4900
Month 12:
Month Name: December
Sales Amount: 5100

Output:
Month with maximum sales: June with amount 5700
Month with minimum sales: January with amount 4500


