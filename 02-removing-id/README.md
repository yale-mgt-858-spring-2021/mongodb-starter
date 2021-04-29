Woah, why do we have the objectID still coming up. That number looks messy.
Let's fix the query so that we display the cuisine, name, and borough,
but exclude the _id.

The first few lines of you answer should look something like this.

You can find the full result [here](https://gist.github.com/lmdisch/eb44179a8cc7d944676cc575a5d406b0)

```
  { 
          "borough" : "Queens", 
          "cuisine" : "Delicatessen", 
          "name" : "Sal'S Deli" }
  {
          "borough" : "Brooklyn",
          "cuisine" : "American ",
          "name" : "Mejlander & Mulgannon"
  }
  {
          "borough" : "Manhattan",
          "cuisine" : "Continental",
          "name" : "Dining Room"
  }
  {
          "borough" : "Manhattan",
          "cuisine" : "American ",
          "name" : "Serendipity 3"
  }
  {
          "borough" : "Staten Island",
          "cuisine" : "Italian",
          "name" : "Crystal Room"
  }

```