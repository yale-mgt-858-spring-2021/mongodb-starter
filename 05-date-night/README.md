Let's get a bit more specific about our restaurant choices. We are going
on a date and we only want restaurants that scored more than 85.
Write a query that only displays these restaurants.

Your results should look like this
```
{ "_id" : ObjectId("15151abdsca13534adaa"),
"address" : {
"building" : "420",
"coord" : [ -53.01518, 40.848447 ],
"street" : "Whitney", "zipcode" : "06511" },
"borough" : "New Haven",
"cuisine" : "Bakery",
"grades" : [
{ "date" : ISODate("2014-03-03T00:00:00Z"), "grade" : "A", "score" : 2 },
{ "date" : ISODate("2013-09-11T00:00:00Z"), "grade" : "A", "score" : 6 },
{ "date" : ISODate("2013-01-24T00:00:00Z"), "grade" : "A", "score" : 142 },
{ "date" : ISODate("2011-11-23T00:00:00Z"), "grade" : "A", "score" : 86 },
{ "date" : ISODate("2011-03-10T00:00:00Z"), "grade" : "B", "score" : 14 }
],
"name" : "Logan's Bake Shop",
"restaurant_id" : "100"
}
```