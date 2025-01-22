# CS121BubblesAndPointers

## include and constants
+ stdio.h
+ constant MAX = 9

## functions decleration
+ void printValues(int value of)
+ void sort(int value of)
+ void swap(int value of, int value of)

## main
+ int values = 7, 3, 9, 4, 6, 1, 2, 8, 5
+ print before values
+ use printValues function for this

### swap test
+ int numOne = 3
+ int numTwo = 5
+ print out the nums
+ use swap function with numOne and numTwo
+ print out the nums

### sort
+ use sort function with values
+ print after values
+ use printValues function for this

## printValues
+ void printValues(int value of values)
+ declare int i
+ print "["
+ for i from 0 to MAX - 1:
+   print values[i]
+ print "]"

## sort
+ void sort (int value of values)
+ declare int i
+ declare int  j
+ for i from 0 to MAX-1:
+   for j from 0 to MAX-1:
+     if values[j] > values[j+1]:
+       swap values[j] and values[j+1]
+       printValue of values

## swap
+ swap(int value of x, int value of y)
+ value of x = value of x + value of y
+ value of y = value of x - value of y
+ value of x = value of y - value of x
