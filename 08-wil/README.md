You just remembered that you have a friend that you met at business school
who was telling you about the best restaurants in the region.
Unfortunately, those $1.00 tequila shots that you miss at Gryphon's has
messed with your memory. You think it starts with 'Wil' but can't really
remember the rest. You should be getting the hang of what your output
queries should be looking like at this point 😊.

Let's write a query that to find the restaurants that contain ^Wil as the
first three letters of its name. Let's get only the `restaurant_id`,
`name`, `borough`, and `cuisine` fields. Your results should look like this.

```
{ "borough" : "Brooklyn", "cuisine" : "Delicatessen", "name" : "Wilken'S Fine Food", "restaurant_id" : "40356483" }
{ "borough" : "Bronx", "cuisine" : "American ", "name" : "Wild Asia", "restaurant_id" : "40357217" }
{ "borough" : "Bronx", "cuisine" : "Pizza", "name" : "Wilbel Pizza", "restaurant_id" : "40871979" }
```