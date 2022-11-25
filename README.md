## c_budget_dynamic_strings

c_budget_dynamic_strings is a simple command line app which stores transactions in a file called budget.txt. Take a look at the budget.txt file to see the structure of the data storage system.

With c_budget_dynamic_strings, you can create a new transaction, read all transactions, update a transaction, or delete a transaction.

To compile and link c_budget_dynamic_strings's source files, I am using GCC and Make. You can compile c_budget_dynamic_strings using the following steps:

1. Download all the source files and the makefile into your chosen directory.
2. Point your terminal to the directory.
3. Use the makefile included with c_budget_dynamic_strings to compile and link the source files.
4. If you have installed Make, run the following command: make c_budget_dynamic_strings

I plan to use various data structures to improve c_budget. I am rebuilding c_budget in the following order (please see my other repositories for various versions of c_budget):

1. c_budget (original)
2. c_budget_2d_array
3. c_budget_array_of_structures
4. c_budget_dynamic_strings
5. c_budget_linked_list
6. c_budget_ordered_list

Also, you can compile c_budget_dynamic_strings on Windows using the following command:

- cl -W4 c_budget_dynamic_strings.c crud_operations.c menus.c read_input.c validation.c -link -out:c_budget_dynamic_strings.exe
