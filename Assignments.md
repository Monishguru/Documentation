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
