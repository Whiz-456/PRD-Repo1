---
nav_order: 2
---

# SWAPI Reference—Endpoint: /people/id/
## Resource
people
The people resource indicates an individual person or character within the Star Wars universe.
## Introduction
This API fetches the details of a specific person or a character based on the id within the Star Wars universe.
## Base URL
https://swapi.py4e.com/api/

The Base URL is the root URL for all the Star Wars APIs and provides information on all the available resources within the SWAPI.
If you ever make a request to SWAPI and you get back a 404 NOT FOUND response then check the Base URL first.
## Endpoint
/people/id/ - get details of a specific person or character within the Star Wars universe people resource
## Method
GET
## Request URL
https://swapi.py4e.com/api/people/{id}
## Example URL
https://swapi.py4e.com/api/people/1/
## Path Parameters
| Parameters | Data Type | Examples of Values | Description |
| ---------- | --------- | ------------------ | ----------- |
| id         | number    | "1"                | There are 87 people resources. Use values from 1 to 87.	Unique id of the person or the character from the people resource in the Star Wars Universe |
