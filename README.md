# Django Exercise

This is a Django exercise for WORK JAPAN that requires you to build a simple backend system to manage various company addresses.

<br>

## Task Details

- Design a database schema (create necessary models) to store postal addresses of various companies. Address consists of the following components (sorted by increasing order of geographic area):
  - Company Name (To be unique, for simplicity)
  - Building number
  - Postal code
  - Locality
  - City
  - State
- For simplicity, consider, a `Postal Code` can only be inside a single `Locality`.
- Create the following RESTful APIs (Authentication not required):
  1. To create/read/update/delete company addresses.
  2. To retrieve address of a company by providing company name.
  3. To list all the companies in a certain city.
  4. To retrieve all the `Postal Code`s which has more than `X` number of companies. `X` to be supplied to the API as URL parameter.
- Follow *PEP 8 -- Style Guide for Python Code*.

**Bonus Points:**

- Write test cases.
- Use Django REST framework for creating APIs.
- Use Python 3.
- Use latest stable versions of the packages.

<br>

## Assessment

- Clean readable code is preferred over a feature rich app.
- Implementing any extra features that are not mentioned in this document will not give you any extra points.


<br>

## Deliverables

1. A zip file of your code. DO NOT push your code to GitHub.
2. Instructions about how to run your code on our local machine. This information may go to `README.md` file.
3. API Documentations.

