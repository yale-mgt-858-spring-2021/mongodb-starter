You're probably thinking this is a huge collection of documents.
I only want the restaurants in each neighborhood. Write a query to display
all the restaurants that are in the borough Queens. As per the previous 
questions, only show the borough, cuisine, and name, while excluding _id

The first few lines of you answer should look something like this.
  
You can find the full result [here](https://gist.github.com/lmdisch/3937dc305fe0824e78f07f0e8698bedf)


  ```
    {       
            "borough" : "Queens", 
            "cuisine" : "Delicatessen", 
            "name" : "Sal'S Deli" 
    }
    {   
            "borough" : "Queens", 
            "cuisine" : "American ", 
            "name" : "Blarney Bar" 
    }
    {
            "borough" : "Queens",
            "cuisine" : "Chinese",
            "name" : "Jardin De China Rest"
    }
    {
            "borough" : "Queens",
            "cuisine" : "Pizza/Italian",
            "name" : "Jack'S Pizza & Pasta"
    }
  ```