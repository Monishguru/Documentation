# 1 Assignment: Understanding Classes and Objects in Java

## Objective:
To understand how classes and objects are created and how the `toString()` method is overridden in Java.

## Problem Description:
Create a class `Employee` with the following data members:
- `empId`
- `empName`
- `businessUnit`
- `projectCode`
- `jobLevel`

The class should have the following member functions:
- Getters and setters for all data members
- Override the `toString()` method to print output in the following format:
  ```
  Emp ID: 4584247
  Emp Name: Elon Musk
  Business Unit : E&R
  Project Code: JAVA_CBE
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
- If “businessUnit” is not entered, the default value for ibu must be set to “BENCH” and
the value for projectCode must be defaulted to “BENCH_CBE2”
- If “businessUnit” is provided but “projectCode” is not entered, the value for
projectCode must be defaulted to “BENCH_<businessUnit>_CBE2”. The <businessUnit> is to be
replaced by the value of businessUnit.

# Assignment 3: Understanding Method Overriding
## Objective: Understanding Method Overriding.

Problem Description: Modify the above program  to override method equals(), so that it
returns true if empID of two objects is same.
