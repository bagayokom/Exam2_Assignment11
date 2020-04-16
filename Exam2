# Howard Lichtman
# Edited by Mohamed B
# April 10, 2020
# Main program to test sort algorithms

import random
import Search_Methods
import time

# redundant code, so make a method!
def fill_list():
    qty = int(input("How many values would you like in the list to be sorted?"))
    for i in range(1, qty + 1):
        my_list.append(random.randint(1,100001))
    print("The list has been filled with random values and now contains:")
    print(my_list)
    return qty

choice = 0

while choice != 6:
    # clears the list
    my_list = []

    print("Please make a selection from the menu below:")
    print("1. Bubble Sort")
    print("2. Selection Sort")
    print("3. Insertion Sort")
    print("4. Merge Sort")
    print("5. Quick Sort")
    print("6. Quit Program")

    choice = int(input(">"))

    if choice == 1:
        print("You have selected a Bubble Sort!")
        qty = fill_list()

        # some new code to keep track of how long the method took
        start_time = time.time()

        my_list = Search_Methods.bubble_sort(my_list)
        # prints the time taken to run the sort
        print(f"** It takes {(time.time() - start_time)} seconds to complete a Bubble Sort with {qty} values **")
        # Added this to look at the output easier
        cont = input("(Input anything to continue..)")
        print(cont)
        print("\nAfter sorting the list with Bubble Sort, the list looks like the following:")
        print(my_list)
        # ** It takes 21.316147804260254 seconds to complete a Bubble Sort with 10,000 values **

    elif choice == 2:
        print("You have selected a Selection Sort!")
        qty = fill_list()
        start_time = time.time()
        my_list = Search_Methods.selection_sort(my_list)
        print(f"** It takes {(time.time() - start_time)} seconds to complete a Selection Sort with {qty} values **")
        cont = input("(Input anything to continue..)")
        print(cont)
        print("\nAfter sorting the list with Selection Sort, the list looks like the following:")
        print(my_list)
        # ** It takes 8.636603116989136 seconds to complete a Selection Sort with 10,000 values **

    elif choice == 3:
        print("You have selected a Insertion Sort!")
        qty = fill_list()
        start_time = time.time()
        my_list = Search_Methods.insertion_sort(my_list)
        print(f"** It takes {(time.time() - start_time)} seconds to complete a Insertion Sort with {qty} values **")
        cont = input("(Input anything to continue..)")
        print(cont)
        print("\nAfter sorting the list with Insertion Sort, the list looks like the following:")
        print(my_list)
        # ** It takes 9.549867391586304 seconds to complete a Insertion Sort with 10,000 values **

    elif choice == 4:
        print("You have selected a Merge Sort!")
        qty = fill_list()
        start_time = time.time()
        my_list = Search_Methods.merge_sort(my_list)
        print(f"** It takes {(time.time() - start_time)} seconds to complete a Merge Sort with {qty} values **")
        cont = input("(Input anything to continue..)")
        print(cont)
        print("\nAfter sorting the list with Merge Sort, the list looks like the following:")
        print(my_list)
        # ** It takes 0.0735623836517334 seconds to complete a Merge Sort with 10,000 values **

    elif choice == 5:
        print("You have selected a Quick Sort!")
        qty = fill_list()
        start_time = time.time()
        my_list = Search_Methods.quick_sort(my_list)
        print(f"** It takes {(time.time() - start_time)} seconds to complete a Quick Sort with {qty} values **")
        cont = input("(Input anything to continue..)")
        print(cont)
        print("\nAfter sorting the list with Quick Sort, the list looks like the following:")
        print(my_list)
        # ** It takes 0.06980133056640625 seconds to complete a Quick Sort with 10,000 values **

    elif choice == 6:
        print("Thank you using the program!")

    else:
        print("You have entered an invalid menu option!\n")


