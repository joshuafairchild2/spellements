# ***Spelling With Elements***

*JavaScript logic exercise, 04/08/2017*

**By Joshua Fairchild**


---

## Description
This is an application that in simplest terms takes an input from the user (intended input is a single word) and transforms the capitalization of the input, then displays it to the user along with some more relevant information.

The capitalization of the input is adjusted so that the word appears to be made of elemental symbols, for example "coffees" would become "CoFFeEs" (Co for cobalt, F for fluorine, Fe for iron, Es for einsteinium). This is not possible for every word, so the application does its best to "elementify" each word as much as possible.

In addition to the newly transformed word, the user is also shown a bit more information about their input. A table is displayed, providing some data pertaining to each element used (name, symbol, number, weight), as well as the "atomic weight" of the individual word (the cumulative atomic mass of the elements present within the word).


#### Basic Specifications
| Behavior | Example Input | Example Output |
| ------   | ------------- |----------------|
| Application will recognize any present elemental symbols and capitalize them accordingly | coffees | CoFFeEs |
| Application will recognize as many elements as possible within words that aren't fully comprised of elemental symbols | spelling | **SP**el**LiN**g |
| Application will not accept invalid entries | _user enters one of the following:_ <ul><li>"" or "  "</li><li>only punctuation</li><li>a number</li><li>word containing no elemental symbols</li></ul>   | _modal window appears instructing the user what went wrong_ |  

----
#### Setup/Installation
* Clone this repository `git clone https://github.com/joshuafairchild1/spellements`

* Navigate to "index.html" within the root directory and open it with any modern web browser

* The webpage can also be viewed [here](https://joshuafairchild1.github.io/spellements/)

#### Technologies Used
* HTML
* CSS with Bootstrap
* JavaScript with jQuery


#### Legal

This software is licensed under the MIT license

Copyright (c) 2017 Joshua Fairchild
