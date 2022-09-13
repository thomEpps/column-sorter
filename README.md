# column-sorter
A super light weight masonry style layout generator using CSS flexbox &amp; jQuery

## Usage
- Add the css & js files to your project. This requires jQuery to work, so reference the column-sorter.js file after jQuery in your footer
- Add a class of `cols` to the target parent element. The children will be sorted in to a masonry style layout
- Use the optional data attribute `data-cols` on the parent element to specify the number of columns to sort in to (on desktop)


## Example HTML
```
  <div class="cols" data-cols="3">
    <div class="item">
      <img src="https://via.placeholder.com/500x400">
      <h2>Card Item</h2>
    </div>
    <div class="item">
      <img src="https://via.placeholder.com/500x800">
      <h2>Card Item</h2>
    </div>
    <div class="item">
      <img src="https://via.placeholder.com/500x300">
      <h2>Card Item</h2>
    </div>
    <div class="item">
      <img src="https://via.placeholder.com/500x600">
      <h2>Card Item</h2>
    </div>
  </div>
```
