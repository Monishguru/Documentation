# 1 Assignment: Understanding Classes and Objects in Java

## Objective:
To understand how classes and objects are created and how the `toString()` method is overridden in Java.

## Problem Description:
Create a class `Employee` with the following data members:
- `empId`
- `empName`
- `ibu`
- `projectCode`
- `jobLevel`

The class should have the following member functions:
- Getters and setters for all data members
- Override the `toString()` method to print output in the following format:
  ```
  Emp ID: 608534
  Emp Name: Navin Israni
  IBU: E&R
  Project Code: JEE_PUN2
  Job Level: 3
  ```

Accept data for one object and display it.

## Program Restrictions:
- None of the data members should be accessible outside the class directly; they should be accessible only through their getter/setter methods.
- Display the data of the employee object using the overridden version of the `toString()` method.
- `Job Level` must be alphanumeric.

# Assignment 2: Understanding Parameterized Constructors

## Objective: Understanding Parameterized Constructors.

Problem Description: Modify the above program 2 to incorporate following restrictions:
- The user need not enter all data while creating the object.
- If “ibu” is not entered, the default value for ibu must be set to “BENCH” and
the value for projectCode must be defaulted to “BENCH_Pune2”
- If “ibu” is provided but “projectCode” is not entered, the value for
projectCode must be defaulted to “BENCH_<ibu>_Pune2”. The <ibu> is to be
replaced by the value of ibu.

# Assignment 3: Understanding Method Overriding
## Objective: Understanding Method Overriding.

Problem Description: Modify the above program  to override method equals(), so that it
returns true if empID of two objects is same.
