Woah, why do we have the objectID still coming up. That number looks messy.
Let's fix the query so that we display the cuisine, name, and borough,
but exclude the _id.

Your solution should look something like this:
```
{ "borough" : "New Haven", "cuisine" : "American", "name" : "Bar Restaurant"}
{"borough" : "West Haven", "cuisine" : "Bakery", "name" : "Pistachio Cafe" }

```