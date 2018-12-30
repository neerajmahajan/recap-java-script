# recap-java-script
Repository to revise and document  javascript

##### Inbuilt Java Script Functions

* prompt("message") : Opens a dialog box with the specified message and wait for user input.
* alert("message") : Opens a dialog box and display the message.
* console.log("message") : log the messages on console.

#### Variable declaration

* var variableName = value;

#### Arrays

```
var movies = ['Me Before You',"Marry Poppins Returns", 'A star is born', 'Bohemian Rhapsody']

// Iterating an array and applying function on array values

movies.forEach(function(movie){
	console.log(movie);
	}
);

	OR
	
movies.forEach(movie => console.log(movie));

	OR
for (var movie of movies){
    console.log(movie);
}

```
