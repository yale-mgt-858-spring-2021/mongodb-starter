Let's start by viewing all the documents in the 'restaurants' database.
This will give us a good preview of the all the documents stored.

Your answer should look something like this.
```
{
  "_id" : ObjectId("6089abbd9e30002f3f868395"),
  "address" : {
          "building" : "97-22",
          "coord" : [
                  -73.8601152,
                  40.7311739
          ],
          "street" : "63 Road",
          "zipcode" : "11374"
    },
    "borough" : "Queens",
    "cuisine" : "Jewish/Kosher",
    "grades" : [
            {
                    "date" : ISODate("2014-11-24T00:00:00Z"),
                    "grade" : "Z",
                    "score" : 20
            },
            {
                    "date" : ISODate("2013-01-17T00:00:00Z"),
                    "grade" : "A",
                    "score" : 13
            },
            {
                    "date" : ISODate("2012-08-02T00:00:00Z"),
                    "grade" : "A",
                    "score" : 13
            },
            {
                    "date" : ISODate("2011-12-15T00:00:00Z"),
                    "grade" : "B",
                    "score" : 25
            }
    ],
    "name" : "Tov Kosher Kitchen",
    "restaurant_id" : "40356068"
}
{
...
```