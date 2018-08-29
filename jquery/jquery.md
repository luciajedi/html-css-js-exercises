# HTML, CSS, JS - Jedi Course
## JQuery Exercises

#### PokeTable

Create a table and some columns:
- Code: Pokémon CODE number
- Normal sprite: it can be back or front but it must be one that is not shiny
- Shiny sprite: same as normal but shiny
- Name: Pokémon name
- Type: if it has more than one type, it should be like "type1 & type2"
- HM: this field can be NULL!

Fill it with AJAX, using [IP]/pokemons. This url works like:
- [IP]/pokemons/ID 
- [IP]/pokemons?id=ID
- [IP]/pokemons?any_field=VALUE like [IP]/pokemons?num=NUM

Also add two buttons to go to the previous/next and an input to search by Pokémon CODE number or Pokémon NAME.
You can disable the buttons with $("#btn").prop("disabled",true); 
If there are no results, or the field is NULL just put "None" or something.

There are only [NUM] IDs.

#### this

Make a web with an input that every time the value is changed, it will show the value + "-".
For example, if you write "a" it will appear "a-" and then if you write "b" it will appear like "a-b-".
Use "this" to change the value.

#### Animations 

Create and animate, with JQuery and CSS animations:

- a div that rotates around vertical axis (Y) and each time it rotates it changes its photo/background
- a div that goes big and small (with buttons for example)
- a div that moves in circles
- a div that fades out (disappear), with a button or with a timer

#### Game

Card Game

Make a "find the pair" game.
- 4x3 rows
- play with both mouse and keyboard 
- when two identical cards are found, they fade out
- timer on top, after 15min it is game over and it should appear on screen
