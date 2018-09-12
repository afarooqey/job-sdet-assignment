# job-sdet-assignment

## Description
The purpose of this assignment is to test your skills in a programming language and basic concepts about Computer Science in general. This will help screen the right candidates for the job at EY.
    
## Assignment

Please write a web service in your language of choice that creates a user profile. Feel free to use any data source (relational, non-relational database, in-memory datastructure, etc.).

A user profile contains the following fields:

```
1. username     | Alphanumeric field - maximum 30 characters
2. first_name   | Alphabets only - maximum 20 characters
3. last_name    | Alphabets only - maximum 20 characters
4. age          | Numeric field - maximum 3 digits
5. id           | UUID field
```

You should provide a RESTful implementation of this web service. 

Pick two of the four endpoints mentioned below. You're welcome to implement all four endpoints but only two endpoints are sufficient.

#### Endpoints

Following are the all the end points provided by this service.

    1. Perform POST profile/new
        * Create the Profile entity with the fields described above.

    2. Perform PUT profile/update
        * Updates username and age fields in the Profile (First & Last name should not be editable once created).

    3. Perform DELETE profile/remove
        * Deletes the profile
    
    4. Perform GET profile/<id>
        * Retrieves username, first name, last name, age if the user exists in the data source.

## Technology Stack

* Implement this solution in your language of choice.
* Use any data source.
* Submit the assignment in a repository on Github.

## Submission Guidelines

When writing a solution for this assignment please consider best programming practices such as 

* naming conventions 
* documentation
* proper unit test coverage
* use of best data structures

Upon completion create a new repository on Github and send the link to your repository.
