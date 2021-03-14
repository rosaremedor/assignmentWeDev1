# Eat Like a Venezuelan

  

Eat Like a Venezuelan is a website that contains recipes of the most popular Venezuelan dishes available in Dublin. It also provides information about a few restaurants in case the user is not in the mood for cooking. The main purpose of this Website is to provide information about Venezuelan cuisine, promote #eating #arepas and let you know more about my beautiful country

  

## Description

CSS Style Used

  

Please, see below all the classes used in this assignment.

  
## Text fonts and colour palette used

Roboto, sans-serif with pinks and blue.
Available on: https://theultralinx.com/2017/07/44-beautiful-colour-schemes-from-award-winning-websites/ [example number 33 is the one I used]
```
body {
	font-family: 'Roboto', sans-serif;
	font-size: 18px;
}

h1 {
	color: #AC3B61;
}

h3 {
color: #ff8080;
}

p {
font-family: verdana;
font-size: 20px;
}

a {
text-decoration: none;
}

td {
padding: 10px;
}
```
## iframe
 
With iframe, I've used "Material design box shadows" available at https://codepen.io/sdthornton/pen/wBZdXq. This feature makes it look more professional and makes it easier for the user to find information

  ```
iframe {
border-radius: 10px;
height: 430px;
box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}
```

## Tables 
Tables used to make it look more professional and visually nicer to read the content

```
table {
margin: 0 auto;
}
```

##  Uppercase style
This class was created to change from lower case to upper case the title of the website
```
.title {
text-transform: uppercase;
}
```
  

##  Subtitle style
Definition of class subtitle to be able to have the same subtitle colour across all the pages
```
.subtitle {
color: #123C69;
}
```

## Contains size
Defined the size that contains the text and the alignment
```
.container {
	width: 90%;
	margin: 0 auto;
	text-align: center;
}
```

 ## Other fancy roles style
 ``` 
.main_content {
	width: 90%;
	margin: 0 auto;
	text-align: center;
}

.guarantee {
background-color: #EEE2DC;
color: #123C69;
margin: 0 auto;
padding: 10px;
box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
border-radius: 2px;
text-align: left;
}

.iframe-container {
	position: relative;
	width: 100%;
	padding-bottom: 56.25%;	
	height: 0;
}

.iframe-container {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
}

.banner_img {
	width: 100%;
	height: 350px;
}

.wrapper_btns {
	display: flex;
	flex-direction: row;
	justify-content: center;
}

.wrapper_btns button {
	background-color: #AC3B61;
	margin: 0 10px;
	border: 0;
	padding: 10px 15px;
	border-radius: 5px;
	box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}
.wrapper_btns a {
	font-size: 18px;
	color: #EEE2DC;
}

.recipe_title {
     /*includes all the subtitles of the tabs*/
	color: #AC3B61;
}


.basic_style_img {
	display: block;
	margin: auto;
	border-radius: 2px;
	box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
}

.beach_img, .descr_beach {
	width: 460px;
	height: 250px;
}

.descr_beach {
width: 660px!important;
}


.recipe_img {
	width: 230px;
}

.restaurants_img, .descr_restaurant {
	width: 368px;
	height: 269px;
}

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.
## License

[MIT](https://choosealicense.com/licenses/mit/)



