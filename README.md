# Sequential Search Algorithm

This C++ program reads a file of employee information and allows the user to search for specific employees by ID number. It also calculates the average number of comparisons required to find an employee.

## Getting Started

To run this program, you must have Visual Studio installed on your system.

### Prerequisites

This program requires Visual Studio 2019 or later to run.

## Running the Program

To run the program, please follow the instructions below:

1. Open the solution file (Sequential Search.sln) in Visual Studio.
2. In the Solution Explorer, right-click on the project and select Properties.
3. In the Project Properties dialog, select the Debug tab.
4. Under the Debugging section, locate the Command Arguments field.
5. Enter the path to your input file in the Command Arguments field.
6. Save the changes and run the program.

Note: The program requires a single command-line parameter, which is the path to the input file. If the path is not provided, or the file cannot be found, the program will report an appropriate error message.

## Input File Format

The input file should be formatted as follows:

- The first line should be a single integer, `n`, indicating the number of employees in the file.
- The next `n` lines should contain the employee information, with each line containing the following fields, separated by vertical bars (pipes):
  - Name
  - ID number
  - Age
  - Job title
  - Hire date
- The next line should be a single integer, `q`, indicating the number of queries to be made.
- The next `q` lines should contain a single integer, the ID number of an employee to be searched for.

Here is an example input file:

5

Oogle Tiweki|20|29|Analyst|2013

Belwit Rywymipo|54|24|Consierge|2019

Boswell Tydedu|7|51|Programmer|2011

Zilbo Duhene|67|59|Consultant|2013

Moodock Rejo|77|48|Consultant|2016

2

67

54

## Output

For each query, the program will output the name, age, job title, and hire date of the employee that was found, along with the number of comparisons required to find that employee. At the end, the program will output the average number of comparisons required per query.

Here is an example output for the input file shown above:

FOUND: Name: Zilbo Duhene, Age: 59, Job: Consultant, Hired: 2013 at index 3 after 4 comparisons.

FOUND: Name: Belwit Rywymipo, Age: 24, Job: Consierge, Hired: 2019 at index 1 after 2 comparisons.

Done! Average amount of work per query: 3.0 comparisons.


## Acknowledgments

This program was created as part of a programming exercise, and is not intended for commercial use.

