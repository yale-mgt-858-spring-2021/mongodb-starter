Notice something weird. It is sometimes normal to think that the query above
will only specify restaurants that explicitly scored 85 or higher. We note
that the query above includes restaurants even if they scored below 85 at
a specified date.

Let's get more specific with our criteria. Find establishments that have
a score greater than 85 but less than 100. Your solution should look like
the one displayed above but with the specified score ranges. Results should 
look similar to the previous question but with fewer results.

Your results should look like as follows (please make sure you get only
the fields shown).

You can find the full result [here](https://gist.github.com/lmdisch/13348b90eab3b9c59b01255c36ec3f3e)

```
  {
          "borough" : "Manhattan",
          "cuisine" : "Pizza/Italian",
          "name" : "Bella Napoli"
  }
  { 
          "borough" : "Manhattan",
          "cuisine" : "Indian",
          "name" : "Gandhi" }
  {
          "borough" : "Manhattan",
          "cuisine" : "American ",
          "name" : "West 79Th Street Boat Basin Cafe"
  }
```