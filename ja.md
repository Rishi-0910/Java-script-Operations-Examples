```
###<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Examples in JS Operations</title>
</head>
<body>
    <h1>Javascript Comparsion Operation</h1>
    <h3>let check-out Example.</h3>
    <p><b> let assume creating a system where developer need to compare a user's age to see movies according to their ages </b></p>
    <script>
        const userAge=18;
        let moviesSuggested;

         // now comparing userage by if-else-if condition
         if(userAge<13)
         {
            moviesSuggested="Aladdin (2019) , Chhota Bheem and the Curse of Damyaan , Toy Story"
         }
         else if(userAge>=14 && userAge<18)
         {
            moviesSuggested="The Hunger Games, Spider-Man, Happy-Days"
         }
         else if(userAge>=19 && userAge<24)
         {
            moviesSuggested="Squid Game seasons , Alice in Borderland, MARCO"
         }
         else if (userAge>=25 && userAge<30)
         {
            moviesSuggested="The kamshir files , Black warrent , Dark water"
         }
         else 
         {
            moviesSuggested="No movies for your age group "
         }
        
         // result 
         document.write(`At the age of ${userAge}, you are recommended the following movies:${moviesSuggested}` )

    </script>
    
</body>
</html>
```
