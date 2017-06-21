# The Pokemon cheatsheet

## The main page
Is availible at https://github.com/Kaczmpi/pokemons/blob/master/project/index.html<br />

## The whole project was created using technologies
* Bootstrap - framework,
* Less - stylesheet language,
* jQuery - JS library,
* BackstopJS - tool for regresion testing
* Brackets - code editor.

## Some info
The main page is the cheatsheet containing the Pokemon names, images, types and overall of the statistics.<br />
When you put a mouse on a Pokemon image it rotates by 360 degrees clockwise and when the cursor leaves the image, it rotates 360 degrees counter-clockwise.<br />
I made also a shortlist containing the Pokemon names. They are linked to the anchors in the main list and when you click it, it just smooth scrolls to the anchor.<br />
Each Pokemon Site connects with a [PokeApi](http://pokeapi.co/api/v1/pokemon/) and aquires Pokemon informations by json.<br />

## About tests
I used BacktopJS for regression testing. By this tool one can see the difference by the reference site and the site with manipulated html or css. In the main html file (index.html) i linked the tests.css files which contains the changes that we want to test (how it affect our site). The effect is availible at https://github.com/Kaczmpi/pokemons/tree/master/project/backstop_data/html_report. All the canches can be seen at index.html file and the test result is wrote in README.md file.