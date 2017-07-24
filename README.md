# simple-gallery
An exercise to create a very simple gallery made with jQuery and AJAX.

## Goal

train the loading of data with AJAX, jQuery event handlers and CSS positioning.

## Steps

1. basics (see [simple-slider-step-1.jpg](simple-slider-step-1.jpg))
  1. find (at least) 5 images licensed under creative common (https://unsplash.com/)
  1. create a file `data.json` consisting of an array of object with the keys
    - `author`
    - `src`
    - `link`
    - `title`
  1. load the `data.json` file using `$.getJSON()`
  1. create a "pager" at the bottom of the page, when one of the pager item is clicked
    - it changes the information (image, author name, author link and title) accordingly
    - the clicked item is set to "active" (visually different from other pager items
  2. create a "Next" and "Back" button which when clicked act like clicking on either the next or the previous pager item