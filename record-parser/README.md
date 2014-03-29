# Record Parser

Write a Ruby program to first assemble a single set of records by parsing data from 3 different file formats and then display these records sorted in 3 different ways.

## Goals

* Simplicity/elegance of design
* Adherence to good software engineering principles
* Maintainability (clean, easy to understand code)
* Effective use of the standard library
* Use of unit tests

## Input Data

A record consists of the following 5 fields: last name, first name, gender, date of birth and favorite color. You will be given 3 files, each containing records stored in a different format.

* The pipe-delimited file lists each record as follows:

  LastName | FirstName | MiddleInitial | Gender | FavoriteColor | DateOfBirth

* The comma-delimited file looks like this:
  LastName, FirstName, Gender, FavoriteColor, DateOfBirth

* The space-delimited file looks like this:

  LastName FirstName MiddleInitial Gender DateOfBirth FavoriteColor

You may assume that the delimiters (commas, pipes and spaces) do not appear anywhere in the data values themselves. Write a Ruby program to read in records from these files and combine them into a single set of records.

## Display Requirements

* Create and display 3 different views of the recordset:
 * Output 1 – sorted by gender (females before males) then by last name ascending.
 * Output 2 – sorted by birth date, ascending.
 * Output 3 – sorted by last name, descending.

Ensure that fields are displayed in the following order: last name, first name, gender, date of birth, favorite color.
Display dates in the format M/D/YYYY.

## Restrictions

You may use the core and the standard library, but no gems, to implement your solution.

[Source](http://www.cyrusinnovation.com/code-test-ruby/)
