# Exercise

##Exercise: ft_array manipulations
Allowed functions : None

Create a C program that does the following tasks on an array:

- Generate an array with random number elements specified by the user.
- A function that takes the array and its size as input, and prints out the elements of the array.
- A function to sort the array in ascending order.
- A function that takes an integer value as an argument and removes every occurrence of it in the array, and shift the rest of the elements to the left.
- A function that takes an integer value as an argument and appends it to the end of the array.
- A function to print the largest element in the array.

Here’s how they should be prototyped :

`void generate_array(int* arr, int size);`
`void print_array(int* arr, int size);`
`void sort_array(int* arr, int size);`
`void remove_element(int* arr, int* size, int num);`
`void append_element(int* arr, int* size, int num);`
`void print_largest(int* arr, int size);`

All these functions take the array and its size as arguments. The functions sort_array() and print_array() return void as they do not return any value. But the functions remove_element() and append_element() not only change and return the array but also change and return the size of the array after manipulating it. They therefore take pointers to the size of the array.
# Submissions 
 git push your solution in this repo and hit /submit in Discord