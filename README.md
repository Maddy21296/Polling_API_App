# Polling Api System
Description :
1. We can create question.
2. We can delete Question → (optional: A question can’t be deleted if one of it’s options has votes)
3. We can view question
4. We can create option for question
5. We can delete option → (optional: An option can’t be deleted if it has even one vote given to it)
6. we can vote to particular option for a particular Question .
***

## Requirements
For development, you will only need Node.js and a node global package installed in your environement and mongodb for database.

* Create Question :-
``` localhost:7000/api/v1/questions/create/ ```

* Create Option :-
``` localhost:7000/api/v1/options/:id/options/create/ ```

* View Question :-
``` localhost:7000/api/v1/questions/:id/ ```

* Delete Option :-
``` localhost:7000/api/v1/options/:id/delete ```

* Delete Question :-
``` localhost:7000/api/v1/questions/:id/delete ```

* Add Vote To Option:-
``` localhost:7000/api/v1/options/:id/add_vote ```
