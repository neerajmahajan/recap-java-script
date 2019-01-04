#### CSS

* Collection of rules

#### Rules
* A rule is made up of two components
* Selector and Declaration 
	eg #page-header {font-size: 10px} --- eveything in the div tag with id=page-header will have font size of 10px.

##### Selectors type
* by id 
	* eg #header p {declaration}
* by class 
	* eg .comment div {declaration}
* by element 
	* eg li {declaration}
	
##### Declaration
* properties
* values
* format
	{property:value;}
	* ```eg {
		font-size:10px;
		color:red;
	}
```

##### Order of rules (Waterfall order)
* new rule down the order override previous rule. 
* If selectors are identical, bottom most selector rules.
* inline style overrides external styles.
* some elements doesn't take style defined in css for eg 'a' has default style which will not take global style, unless a is overrident in css.
###### Selector Specificty
* If a rule is more specific, then that rule wins irrespective of order. order of preference
	* eg
	```
		#divId p{color:red}; // This rule wins for specific p tag
		p {color:green}
		
	```
* Order of preference
	* id
	* classes
	* elements

##### Inheritance 
* If we apply any style to parent tag, then that style will be applied to all its childs and sub childs.