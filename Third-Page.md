---
nav_order: 3
parent: SWAPI Overview
---

# SWAPI Reference—Endpoint: /people/
## Resource
people
A people resource is an individual person or character within the Star Wars universe.
## Introduction
This API lists the details of all the characters and people within the Star Wars universe.
## Base URL
https://swapi.py4e.com/api/

The Base URL is the root URL for all the Star Wars APIs and provides information on all the available resources within the SWAPI.
If you ever make a request to SWAPI and you get back a 404 NOT FOUND response then check the Base URL first.
## Endpoint
/people/ - get all the people resources within the Star Wars universe
## Method
GET
## Request URL
https://swapi.py4e.com/api/people/
## Query Parameters
| Parameters |	Data Type |	Values | Description |
| ---------- | ---------- | ------ | ----------- |
| name |	string |	"luke" |	The person's name or the character name by which the resource data is filtered. |
## Sample Response
```
{
    "count": 87,
    "next": "https://swapi.py4e.com/api/people/?page=2",
    "previous": null,
    "results": [
        {
            "name": "Luke Skywalker",
            "height": "172",
            "mass": "77",
            "hair_color": "blond",
            "skin_color": "fair",
            "eye_color": "blue",
            "birth_year": "19BBY",
            "gender": "male",
            "homeworld": "https://swapi.py4e.com/api/planets/1/",
            "films": [
                "https://swapi.py4e.com/api/films/1/",
                "https://swapi.py4e.com/api/films/2/",
                "https://swapi.py4e.com/api/films/3/",
                "https://swapi.py4e.com/api/films/6/",
                "https://swapi.py4e.com/api/films/7/"
            ],
            "species": [
                "https://swapi.py4e.com/api/species/1/"
            ],
            "vehicles": [
                "https://swapi.py4e.com/api/vehicles/14/",
                "https://swapi.py4e.com/api/vehicles/30/"
            ],
            "starships": [
                "https://swapi.py4e.com/api/starships/12/",
                "https://swapi.py4e.com/api/starships/22/"
            ],
            "created": "2014-12-09T13:50:51.644000Z",
            "edited": "2014-12-20T21:17:56.891000Z",
            "url": "https://swapi.py4e.com/api/people/1/"
        },
        {
            "name": "C-3PO",
            "height": "167",
            "mass": "75",
            "hair_color": "n/a",
            "skin_color": "gold",
            "eye_color": "yellow",
            "birth_year": "112BBY",
            "gender": "n/a",
            "homeworld": "https://swapi.py4e.com/api/planets/1/",
            "films": [
                "https://swapi.py4e.com/api/films/1/",
                "https://swapi.py4e.com/api/films/2/",
                "https://swapi.py4e.com/api/films/3/",
                "https://swapi.py4e.com/api/films/4/",
                "https://swapi.py4e.com/api/films/5/",
                "https://swapi.py4e.com/api/films/6/"
            ],
            "species": [
                "https://swapi.py4e.com/api/species/2/"
            ],
            "vehicles": [],
            "starships": [],
            "created": "2014-12-10T15:10:51.357000Z",
            "edited": "2014-12-20T21:17:50.309000Z",
            "url": "https://swapi.py4e.com/api/people/2/"
        }
     ]
}
```
