## Stained Glass Window

Stained-Glass is a design experiment originally inspired by a pixellated stained glass window made by [Gerhard Richter](http://media.tumblr.com/tumblr_lz4rky6FKd1qggdq1.jpg).

The page is currently hosted here: [http://bradreeder.github.io/Stained-Glass-Window/index.html](http://bradreeder.github.io/Stained-Glass-Window/index.html)

#### What

Three column grid-design. Each box of the grid is composed of hundreds of smaller divs that intermittently change colour in a random pattern. When any of the coloured boxes are clicked on, that colour is removed from the overall palette. When all the colours are removed, the user can click again and it refreshes to its initial state.

#### How

Currently this is done dynamically. The entirety of the grid is generated by javascript and then coloured (through assigning the individual divs a random colour class) from a pre-defined array of colours. A timer is set so that every 100ms it fills again randomly from the same array. When one of the boxes is clicked on an event fires that removes that colour from the potential palette. When the colour array is empty it refreshes to its original condition.

#### Current Goals

* Use canvass/sass/css3 to create a [rose-window](https://enthusiastical.files.wordpress.com/2013/04/dsc02086a.jpg)
* and to add semi-circles to the top of the current windows to shape them more. 
* Proportion the window's sizes better and perhaps increase their length so you can scroll down them. 
* Work on more interesting colour patterns to implement.

#### Stretch Goals

* Considering extending the basic design into an idea for a [hypercomic](https://en.wikipedia.org/wiki/Hypercomics).
