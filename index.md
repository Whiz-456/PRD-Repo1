# SWAPI Overview
## What is SWAPI?
The Star Wars API (SWAPI) is the world's first quantified and programmatically-accessible data source for all the data from the Star Wars canon universe! You can consume all the rich contextual stuff from the Star Wars universe using SWAPI.
## Why should I use the SWAPI?
The SWAPI provides a wealth of data about the Star Wars universe to build applications. With the SWAPI, developers can access detailed Star Wars related data about people, planets, films, species and much more. From web and mobile applications to data analysis, the possibilities are limitless.

All the data is accessible through the SWAPI'S HTTP web API.
Visit https://swapi.dev/ and https://swapi.dev/documentation to learn more.
Helper libraries for popular programming languages are also provided so you can consume SWAPI in your favourite programming language, in a style that suits you.
## How to use the SWAPI?
Here are a few examples of what developers can build using the SWAPI:
- Create a Star Wars encyclopedia to document the Star Wars universe and its characters.
- Design a custom interactive map to explore the planets of the Star Wars universe.
- Analyze the data to uncover patterns and insights about Star Wars films, characters, and species.
- Design a search engine to query Star Wars related data.
- Create a mobile app that displays information about the characters, films and species in the Star Wars universe.
- Design a live score system specialized in providing stats related to the Star Wars films and characters.
## Authentication
The SWAPI does not require authentication.
It is a completely open API. No authentication is required to query and get data. This also means that we've limited what you can do to just fetch (GET-ing) the data. If you find a mistake in the data, then tweet the person (https://twitter.com/drchuck) supporting the site.
## Headers
Response Content-Type: application/json
## Return Status Code
SWAPI uses conventional HTTP response codes to indicate the success or failure of an API request. In general: Codes in the 2xx range indicate success. Codes in the 4xx range indicate an error that failed given the information provided (for example, a required parameter was omitted, etc.)
## Rate limits
SWAPI has a rate limit to prevent malicious abuse (as if anyone would abuse Star Wars data!) and to make sure our service can handle a potentially large amount of traffic. Rate limiting is done via IP address and is currently limited to 10,000 API request per day. This is enough to request all the data on the website at least ten times over. There should be no reason for hitting the rate limit.
