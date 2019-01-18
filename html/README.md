##### HTML - A Markup language
* Text to be markup is put into <></> tags.
* Every html page should have extension .html

##### Tags 
* Different tags exist for various representations.
* A tag can have attributes. There are some global attributes like **class** **style** which can be applied to any tag, while some attributes are specific to a specific tag.
* Tags are normally intended when nested.
* Always put text in tags.

#### Editors
* http://brackets.io/#

##### Anchor tag a
* External link
* Internal link
* download link -- for files
* link to specific areas on page

##### Lists
* Unordered list  <ul> + <li>
* Ordered list	 <ol> + <li>
* Definition list <dl> + <dt> + <dd>

##### Div tag (used for division)
* Used to divide content into logical sections.
* has **id** and **class** as attributes
* An id is a unique identifier on a page.
* A class is an idenfier which can be repeated multiple times on a page inside div tag.

##### Style A style is used to decorates an html tag/s
* inline style (Bad practice, results in lot maintenance and effort)
* style definition in header section (Better than inline style, but still a Bad practice, results in lot maintenance and effort)
* Defining all styles in CSS file and linking it through header.

#### Adding Java Script
* in the script tag in the head or body.
* By linking a .js file in the head or body.
* Inline (not a good practice)

https://www.html5rocks.com/en/tutorials/
https://docs.webplatform.org/wiki/html

#### FORMS

* placeholder
* label for
* required
* email
* maxlength

```
<form action="" method="post"> // action specifies where form info to be submitted. default is same page
	<input type="text" id="firstName" name="firstName"> // name goes to server as key
	
	<input type="text" id="userName" name="userName" placeholder="Default User Name"> // Greyed value to help user.
	
	<label for="firstName">FirstName</label> // value in for is mapped to id
	 
	<br>
	
	<input type="text" name="lastName" value="Mahajan" required> // required attribute make it mandatory to have that field, otherwise on submission browser will give error
	
	<input type="email" name="email"> // email is HTML5 type, the input text is validate on submission to have an email format.
	
	<input type="submit" name="Click Me to send data to server">
	
	<textarea id="message" rows="4" cols="40" maxlength=400> // maxlength is HTML5 tp define max length of textarea. you can't type more that the defined length.
	
	
</form>

```


```
<form action="" method="post"> 

	<input type="color> name="color" > // HTML5 Given user input to select color from color picker
	
	<input type="date> name="birthDate" > // HTML5 Given user input to select date from date picker
	
	<input type="number> name="number" min="10" max="20"> // HTML5 for numeric value
	
	<input type="url" name="homePageUrl" > // HTML5 for url type text
	
	<input type="file" name="cv" > // For uploading files
	
	<input type="range" name="range" min="10" max="50"> eg price range
	
	<input type="datetime-local" name="transactionTime" > // for datetime picker
	
	<input type="checkbox" name="vegOptions" value="Rice" checked> // checked make it checked by default // if not checked then will not passed to form data.
	
	<input type="radio" name"gender" value="Male">
	<input type="radio" name"gender" value="Female">
	
	
</form>

```

```
<form> 

	<select name="host_type">		// Shows a comboxox
		<option value="aws">AWS</option>
		<option value="azure" selected>AWS</option> 	// selected make it default selected in the combobox
	</select>
	
	<input type="password" name="pwd">	
	
</form>

```

```
<form> 

	<fieldset>
		<legend>Required Information<legend> // fieldset Label
		
		<input type="text" id="skinColor" name="skinColor" list="listBelow" > // HTML5 list attribute It is like entering address from pre-defined list of addresses. you just enter some text, it will show available options.
		<datalist id="listBelow" >
			<option>White</option>
			<option>Brown</option>
			<option>Black</option>			
		</datalist>			
		
	</fieldset>
	
</form>

```


	






































