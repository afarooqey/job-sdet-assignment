# assignment-json-search

Given a word (or phrase) search a given JSON object. 

The purpose of this search is to return the title of a movie when a word or phrase is passed. The provided search term should be searched in all values of the object, returning the title(s) wherever the searched term is present. 

At the end it should also show how many times the term was present. 

##### Example
```
[
  {
    "title": "Avengers: Age of Ultron",
    "year": 2015,
    "cast": [
      "Robert Downey, Jr.",
      "Chris Evans",
      "Chris Hemsworth",
      "Mark Ruffalo"
    ],
    "genres": [
      "Action"
    ]
  },
  {
    "title": "The Avengers",
    "year": 2012,
    "cast": [
      "Robert Downey, Jr.",
      "Chris Evans",
      "Mark Ruffalo",
      "Chris Hemsworth",
      "Scarlett Johansson",
      "Jeremy Renner",
      "Tom Hiddleston",
      "Clark Gregg",
      "Cobie Smulders",
      "Stellan Skarsgård",
      "Samuel L. Jackson"
    ],
    "genres": [
      "Superhero", "Action"
    ]
  },
  {
    "title": "Life of Adam",
       "year": 2018,
       "cast": [
         "Adam Smith"
       ],
       "genres": ["History"]
  }
]
```

###### Example  1
```
Input: "Action"
Output: Search Term: "Action" Movies: "Avengers: Age of Ultron", "The Avengers" count: 2
``` 
###### Example  2
```
Input: "Jeremy Renner"
Output: Search Term: "Jeremy Renner" Movie: "The Avengers" count: 1
``` 
###### Example  3
```
Input: "Chris"
Output: Search Term: "Chris" Movie: "Avengers: Age of Ultron", "The Avengers" count: 4
``` 
###### Example  4
```
Input: "Adam"
Output: Search Term: "Adam" Movie: "Life of Adam" count: 2
``` 

#### Purpose
The purpose of this assignment is to demonstrate abilities in the following areas:
1. Use of Data Structures.
2. Recursion vs Iteration.
3. Documentation.
4. Testing.

#### Hints
* It's best to use recursion for this solution.
* Particular emphasis will be paid on how much test coverage you have provided through unit tests.
* Provide extensive negative test coverage.
* Documentation which lists detailed commands on how to build your project will be useful.
* Please do not commit any project IDE files or other unnecessary files. 

#### Technology Stack
* Implement this solution in your language of choice.
* Submit the assignment in a repository on Github.

#### Submission Guidelines
When writing a solution for this assignment please consider best programming practices such as

* naming conventions
* documentation
* proper unit test coverage
* use of best data structures

Upon completion create a new repository on Github and send the link to your repository.
