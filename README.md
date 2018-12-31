# recap-java-script
Repository to revise and document  javascript

* Lightweight (easy to implement)
* Interpreted (Instructions are executed direcly.)
* Object Oriented (We can design and write our code in terms of class and Objects)
* first-class functions (functional programming: functions can be used as value, Functions can be assigned to a variable)
* scripting language (Instructions are given and executed in linear order, but it can be bundled into a file and executed)

#### Runtime environments for Java Script
* Web Browser
* ???

#### Popular Frameworks

##### Client Side
* Jquery
* React
* Angular
* Ember

##### Server Side
* NodeJS
* Express

#### Specification
* ECMA 6

##### Inbuilt Java Script Functions

* prompt("message") : Opens a dialog box with the specified message and wait for user input.
* alert("message") : Opens a dialog box and display the message.
* console.log("message") : log the messages on console.

#### Datatypes

##### Primitive
* Number (64 bit floating value)
* String (16 bit unicode value)
* Boolean (true / false)
* Undefined (only undefined value. It is when we declare any variable and not assign any value)
* Null (only null value. This value can be assigned to any variable, when the actual value is not known.  typeof null shows null, but it is an existing bug)
* Symbol (Added in ECMA 6)

##### Non Primitive
* Array
* JSON
* Object

###### typeof 
* It is used to check the data type of variable or directly value.

```
var name = "neeraj"

typeof name;
```

#### == vs ===

* When we use == to compare two values, javascript do type conversion if the two values are not of same type and then does the comparison. ``` 10 == "10" will return true ```

* === does right comparison. ``` 10 = "10" will return false ```

##### Boolean value : Values of all types has as associated boolean value.
* If we use non zero value in if condition then it will always return true.. for zero it will return false.
* If we use non empty string in if condition then it will always return true... otherwise it will return false.
* null or undefined will also return false.

#### Variable Declaration & Definition

* var variableName; (Declaration)
* var variableName = value; (Definition)
* varibaleName = value (assignment... variable is already declared)
* At any time of script or program, we can change the variable value with **ANY DATA TYPE** (LOOSE TYPING).

#### Arrays

```
var movies = ['Me Before You',"Marry Poppins Returns", 'A star is born', 'Bohemian Rhapsody']
```

##### Iterating an array and applying function on array values
```
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

#### Objects
* Don't have classes( JavaScript is not class based programming language)
* Free Form as not bound to classes (properties  or functions can be added to Object on the fly(dynamixally) and even after creating its object)
* Object Creation
	*	var myObj = {} // Empty Object
	*   myObj.name = "neeraj"; // Added property to myObj Object after object creation.
	*	upfront creating Object
		```
			var employee = {
				"firstName": "John",
				"lastName" : "Jones",
				"salary"   : 56600,
				"vegetarian" : true			
			}		
		```
* Accessing Object property
	* object.propertyName
	* if the property doesn't exist for an Object, then undefined value will be returned.
