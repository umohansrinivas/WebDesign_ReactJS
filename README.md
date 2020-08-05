# WebDesign_ReactJS

###### This repository is made for Web Designing using ReactJS APSSDC FDP

###### 20th July 2020 (Monday) to 31st July 2020 (Friday)

### Day 01
#### What is Web Design ?
             Creating  a website(Static or Dynamic) based on requirement is known as Web Design.
#### What is Web Development ?
               Maintaining the website is known as Web Development(able to perform all DataBase operations).
#### Software Requirements for our project :
                                            1. Text Editor (Sublime Text, Visual studio)
                                            2. Git and Github
                                            3. Chrome
                                            4. Nodejs software
#### Importance of Git and Github in our project:
                    Github is an distributed version control system which maintains the versions of our project.
  ##### Advantages of Github :
                              1. We are able to deploy our project, whenever we want able to get back to previous code by using snapshots
                              2. We can also contribute with other's project 
                              3. open source and also works as social network
 **To create a Github Account** [Official url for Github](https://github.com/)
 #### What is Git ?
                  Git is a tool which manages the snapshots of or project and able to handle small or very large projects effictvely
 **Github uses tool Git to manage the snapshots of the project**
 ##### Installation of Git tool [official website for Git tool](https://git-scm.com/)
 ##### Create a Empty Repository in Github :
                                            1. To create a repository at top-right there is a "+"  dropdown button select that button
                                            2. Select "New Repository" option
                                            3. Name your repository (Repository name should be unique)
                                            4. Make your repository as public (Anyone on the internet are able to see your repository)
                                            5. Initialize your repository with readme file (readme file is completely used for documentation)
                                            6. select option "create repository"
**Readme.md file importance**: 
                            Readme.md file is used for documentation in Github repository by using Markdown syntax
#### Documentation in Markdown format [official url for Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
## Commands in gitBash :
**git config --global user.name "username"** :  This command is used to configure our username into git tool
**git config --global user.mail "mailid"**   :  This command is used to configure our mailid into git tool
**pwd** : This command is used to check the path (pwd stands for present working directory)
**cd Desktop** : This command is used to change our directory to DESKTOP.
**git init** : This command will initialize a git repository 
##### Cloning a Repository from Github Account to local system :
                                                                 1. We have to clone(copy) our repository to local system where we are going to perform our necessary operations to our project
                                                                 2. Cloning a repository will create a folder in localsystem with same name of repository.
  #### How to clone a Repository : 
                                    1. open the repository and then select clone option
                                    2. Copy the url
                                    3. open the gitbash
                                    4. check the path again if you are not in DESKTOP change your path to DESKTOP.
 
 ### Commands to clone a repository using gitBash
 **git clone paste the url** : This commands clone a repository from github and creates a folder in our local system.
 **ls** : This command is used to display the list of files.
**cd foldername** : This command is used to enter into cloned repository
**mkdir css** : This command is used to create a folder
**mkdir image** : This command is used to create a image folder
**mkdir js** : This command is used to create a js folder.
**touch index.html** : This command is used to create a index.html file.
### Commands to push the changes from local folder to Github repository 
**git status** : This command is used to check the status of the git (If the file is in red color i.e. untracked file,if the file is in green color i.e. tracked file)
**git add .** : This command is used to add all the files from untracking area to tracking area.
**git commit -am "commitmessage** : This command is used to save all the changes with a commit message
**git remote** : This command is used to check the remote (by default we have "origin" remote)
**git push origin master** : This command is used to push the changes to github repository.
**Important note if we want to push the changes again(?second time) we have to fetch and pull**
**git fetch origin** : This command is used to fetch the changes to remote.(Here the default remote name is origin)
**git pull origin master** : This command is used to pull the repository in Github.
**git push origin master** : This command is used to push the chnages from localfolder to Github Repository.

## Day 02:

## Introduction to Html5:
                         Html5 stands for Hyper Text MarkUp language used to create web pages and the version is 5.
                         Generally web page is divided into 3 parts:
                                       1. Head part(title,Navigation,Meta)
                                       2. Body part(content)
                                       3. Foot part
                         Html5 uses series of elements to display the content,these elements are enclosed with tags.
                         SYNTAX: <STARTTAG> Content </ENDTAG>
                         
#### Different types of Elements in Html5:
                                          1. Block-level Element 
                                              1.1 All heading tags(h1 to h6)
                                              1.2. paragraph tags(p)
                                              1.3. All Semantic Elements
                                          2. Inline Elements
                                              1.1. span tag
                                              1.2. All navigation Elements
                                              1.3. Image tag
                                              1.4. All form-controllers
                                              
                                          3. Navigation Elements(a,href)
                                             1.1. Inbound Navigation(able to navigate to the content in the same page)
                                             1.2. Outbound Navigation(able to navigate to content present in another file)
                                             1.3. mailto(used to send a mail)
                                             1.4. tel(able to call particular person)
                                           4. Semantic Elements:
                                          Semantic Elements are similar to <div> tags but it contains some description.
                                             1.1. section
                                             1.2. article
                                             1.3. aside
                                             1.4. nav
                                             1.5. header
                                             1.6. footer
                                         
## Day 03

## CSS (Cascading Style Sheets) : Add Beautification to our web page
Syntax: Selector{Property: value;}
Selector is used to select a tag where we want to apply styles.
### Types of Selectors:(All selectors use style attribute in the head part)
                        1. Universal Selector(*): By using Universal selector we are able to apply styles to the entire body part.
                        
                        2. Identifier Selector(#): To use identifier Selector we have to mention a id with name in the tag,identifiers are unique.
                        3. Class Selector (.): To use class Selector we have to mention class with name in the tag,we can use any number of identifiers in a single class(class mostly used in External Css)
                        4. Descendant Selector: Descendant Selector is used we are able to apply style to the tag present in the child and the child present in the parent class
                            .parent>#child(h2)
                        5. child combiner : Child combiner and Descendant Selector are same but different in the syntax only
                            .parent #child(h2)
                        
 ### Types of css:
                     1. Inline css : Inline css is used to apply style within a tag (without using any selector)
                     2. Internal css : Internal css is nothing but we are able to apply styles within a page.
                     3. External css : External css file is nothing but where we can give styles in another file and we are able to apply those styles into our file
                     
                     
                     
## Day 04:
#### Created a Responsive profile using Flex box and metatag,media Queries
##### Post responsive profile in GitHub Pages


## Day 05:

## Day 05 & Day 06 :

### Tables
*  `.table`   =>  Layout for table
*  `.table-dark`
*  `.table-bordered` 
*  `.table-borderless` 
*  `.thead-dark`
*  `.thead-light`
*  `.table-striped`
*  `.table-hover`
#### Attributes for table
*   `colspan`
*   `rowspan`
*   `scope="col|group|colgroup|rowgroup"`
#### Table-responsive-{breakpoint}
*   `.table-responsive`
*   `.table-responsive-sm`
*   `.table-responsive-md`
*   `.table-responsive-lg`
Example:
```
	<!DOCTYPE html>
<html>
<head>
	<title>:: Bootstrap Tables ::</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<meta name="viewport" content="width=device-width,initial-scale=1">
</head>
<body>
	<div class="container mt-5">
		<div class="table-responsive-md">
			<table class="table  table-bordered  ">
	<thead class="thead-dark">
		<tr class="bg-primary">
			<th scope="col">S.No</th>
			<th>Continent</th>
			<th>First_Name</th>
			<th>Last_Name</th>
			<th>Age</th>
			<th colspan="2">Actions</th>
			
		</tr>
	</thead>
	<tbody>
		<tr>
			<td scope="row">1</td>
			<td rowspan="2">Non Asia</td>
			<td>Warren</td>
			<td>Buffet</td>
			<td>69</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
		<tr>
			<td>2</td>
			<td>Jeff</td>
			<td>Bezzos</td>
			<td>65</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
		<tr >
			<td>3</td>
			<td>Asia</td>
			<td >Mukesh</td>
			<td>Ambani</td>
			<td>60</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
	</tbody>
	
    </table>
		</div>
</div>
</body>
</html>
```
### Cards
*  `.card`
*  `.card-header`
*  `.card-body`
*  `.card-footer`
*  `.card-img-top`
*  `.card-title`
*  `.card-subtitle`
*  `.card-text`
*  `.card-link`
*  `.card-group`
*  `.card-deck`
Example:
```
	<!DOCTYPE html>
<html>
<head>
	<title>:: Profile card ::</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<meta name="viewport" content="width=device-width,initial-scale=1">
</head>
<body>
<div class="container mt-5">
	<div class="card-deck">
	<div class="card" style="width:18rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	</div>
</div>
</body>
</html>
```
## Day 06

## JS
###  History of JavaScript
* For implementing the dynamic behaviour of a web site.
* It was called as `live script` in initial stages.
* `Brendan Eich` (Netscape navigator) was introduced this `JavaScript`.(`September 1995`)
* `JavaScript` is an interpreter language.
* He tiedup with ECMA (Ecma Scrpt) - ECMA SCRIPT - 262 (`ES-262`)
* ECMA SCRIPT -2018 is the latest version (`ES-9`)
* For implementing high end JS modules, We've to focus on `ES-6`.
### Data types
* Number
* String
* Boolean
* Function
* Object
* null
* undefined
### Convertion functions
* Number()
* parseInt()
* parseFloat()
### Alerts in JavaScript
* alert()
  ```javascript
      alert("Hi");
  ```
* prompt()
  ```javascript
      prompt("Enter your name");
  ```
* confirm()
  ```javascript
    confirm("Are you sure?");
  ```
  Example:
   ```javascript
        if(confirm("Are you sure?")==true){
	        console.log("Clicked on okay");
        } else {
	        console.log("Clicked on cancel");
        }
   ```
### Console statements
* console.log()
```javascript
	console.log("This is for displaying an output");
```
* console.info()
```javascript
	console.info("This is also for displaying the output");
```
* console.warn()
```javascript
	console.warn("This is a warning");
```
* console.error()
```javascript
	console.error("Oops! this is error2");
```
### Functions:
* Functions without parameters (static functions):
```javascript
	// defining a function
	function add(){
		var a=1;
		var b=2;
		return a+b;
	}
	//Calling the above function
	add()
```
* Functions with parameters (Dynamic functions)
```javascript
	function multiply(x,y){
		return x*y;
	}
	multiply(2,3)
```
* Function without name (**Anonymous functions**)
```javascript
	var object=function(a,b){
		return a*b;
	}
	object(3,4)
	_______
	Output: 12
```
* Arrow functions
```javascript
	var multiply=(x,y)=>{
		return (x*y)
	}
	multiply(5,6);
	______
	Output: 30
```
### Array iteration using map,for-in and for-of
* **Map()**
	* Syntax:
```javascript
	arrayName.map({arrow function})
```
* Example
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	// iter holds the values and index holds the index values of an array
	names.map((iter,index)=>{
		console.log(iter);
		console.log(index);
	})
```
* for-in
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	for(i in names){
		console.log(i);
	}
```
	
* for-of
	
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	for(i of names){
		console.log(i);
	}
```
### Document Object Model (DOM):
* We can implement JavaScript code any where in html document.
* We've to use script tags for taht (`<script> </script>`)
* By using `document` keyword, We can manipulate the data in html document.
* Document object model functions are:
```javascript
		document.getElementById("id");
```
* Collections
```javascript
		document.getElementsByClassName("className");
		document.getElementsByTagName("Tag name");
```
* Common statements for DOM
```javascript
		document.querySelector("#selector | .selector | Tag Name Selector");
		document.querySelectorAll(".selector | Tag Name Selector");
```
### innerHTML
`innerHTML` triggers the information exist with in the tags.
Example:
```html
	<div id="second">
		Sample division
	</div>
```
```javascript
	var second=document.getElementById("second").innerHTML;
	console.log(second);
	____
	Output: Sample division
```
**Writing information into divisions using `innerHTML`**
```javascript
	document.getElementById("second").innerHTML="Hello everyone";
```
**Creating and appending HTML attributes**
We can create the html attributes by using javascript code part also. For that we need to use `document.createElement`. And we can append the information into the created elements by using `textContent`.
Syntax:
```javascript
	document.createElement("html tagname")
```
Example:
```javascript
	//Selecting a section from html;
	var secondDiv=document.getElementById("second");
	
	// Creating a html attribute
	var heading2=document.createElement("h2");
	heading2.textContent="heading";
	
	//Appending child attribute to parent
	secondDiv.appendChild(heading2);
```
## 28-07-2020

## 29-07-20

## 30-07-2020

## 31-07-2020

## 01-08-2020

## 03-08-2020

## 04-08-2020

## 05-08-2020

