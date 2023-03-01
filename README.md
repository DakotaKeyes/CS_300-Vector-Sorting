# CS_300-Vector-Sorting
Vector Sorting Data Structure

The focus of these problems will be working with information extracted from a municipal government data feed containing bids submitted for auction of property. All materials for this assignment can be found in the Supporting Materials section below. The data set is provided in two comma-separated files:

eBid_Monthly_Sales.csv (larger set of 12,023 bids)
eBid_Monthly_Sales_Dec_2016.csv (smaller set of 76 bids)
This assignment is designed to explore sorting algorithms by implementing both a selection sort and quicksort of a vector of bids loaded from a CSV file.

We provide a starter console program that uses a menu to enable testing of the sort logic you will complete. It also allows you to pass in the path to the bids CSV file to be loaded, enabling you to try both files. In this version, the following menu is presented when the program is run:

Menu:

Load Bids
Display All Bids
Selection Sort All Bids
QuickSort All Bids
Exit
Enter choice:

The VectorSorting.cpp program is partially completed. It contains empty methods representing the programming interface used to interact with the linked list. You will need to add logic to the methods to implement the necessary behavior. Here are the methods in VectorSorting.cpp that you must complete:

void selectionSort(vector& bids)

void quickSort(vector& bids, int begin, int end)
int partition(vector& bids, int begin, int end)

Prompt
You will need to perform the following steps to complete this activity:

Setup: Begin by creating a new C++ project with a project type of "Hello World C++ Project".

Name the project “VectorSorting”. Remember to pick the correct compiler in Toolchains and click Finish. This will create a simple VectorSorting.cpp source file under the /src directory.
Download the starter program files and copy them to the project’s /src directory, replacing the existing auto-generated ones. Remember to right-click on the project in the Project Explorer pane on the left and Refresh the project so it adds all the new files to the src folder underneath.
Because this activity uses C++ 11 features, you may need to add the -std=c++11 compiler switch to the miscellaneous settings.

**Task 1: Implement the selection sort algorithm:**

Code the selection sort logic using “bid.title” as the sort field.
Invoke the selectionSort() method from the main() method including collecting and reporting timing results.
Task 2: Implement the quicksort algorithm:

Code the quicksort logic using “bid.title” as the sort field.
Invoke the quickSort() method from the main() method including collecting and reporting timing results.
