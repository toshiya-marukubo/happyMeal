# happyMeal
This is JavaScript file.  
You can eat happy meal as much as you like :)
## Demo
[CodePen](https://codepen.io/toshiya-marukubo/pen/GRjgZMG)
## License
MIT
## How to use
Add something like a button to your site.
After, please execute 'happyMealInit' after set option.
```
// html element
<div id="happy-button">MENU</div>

// call file
<script src="./happyMeal.js"></script>

// execute script (Change the options as you like.)
<script>
  happyMealInit({
    event: 'load', // When to start.
    button_id: 'happy-button', // Your favorite id name (same name as button id).
    min_size: 50, // min happy meal size.
    max_size: 200, // max happy meal size.
    direction_x: -1, // x direction 1 == to right : -1 == to left.
    direction_y: -1, // y direction 1 == to down : -1 == to up.
    mult_x: 10, // multiply to direction_x.
    mult_y: 5, // multiply to direction_y.
    gravity: 0.1, // gravity.
    gravity_random: true // make gravity random number.
  });
</script>
```
