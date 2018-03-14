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
  - To create/update/delete company addresses.
  - To retrieve address of a company by providing company name.
  - To list all the companies in a certain city.
  - To retrieve all the `Postal Code`s which has more than `X` number of companies. `X` to be supplied to the API as URL parameter.

**Bonus Points:**

- Write test cases.
- Use Django REST framework for creating APIs.

<br>

## Assessment

- You can create a GitHub repo and push the code there and then share the repo url.
- Document how to run your code on our local machine.
- Document the APIs (API endpoint, HTTP request methods accepted, Request body format, Response body format, Expected URL parameters, etc.)
- Clean readable code is preferred over a feature rich app.

