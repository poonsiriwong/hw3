# hw3

What code draws the blades of grass?

function draw() {
  stroke(random(60, 70), 100, 90);
  line(x, height-10, x+random(-10, 10), height-10-random(h));
  noStroke();



What code makes the "lawnmower" come by? How often does it come by?
  if (random() > 0.999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
  }

It comes by randomly.

What's the point of the h variable?
It allows the grass to grow taller, but when h = 10, the "lawnmower" will appear.


What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
The -10 becomes the lawnmower when h = 10.
When h <= 9, the grass keeps on growing.


What's the point of an object?
Organize your collection of variables to be used together, to help me keep track of things


What's an example of a range you might use for the map function?



What line of code would give me a random year in the last century?













