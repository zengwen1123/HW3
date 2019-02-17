# HW3
What code draws the blades of grass? 
line(x, height-10, x+random(-10, 10), height-10-random(h))

What code makes the "lawnmower" come by? How often does it come by? 
if (random() > 0.999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
it comes by when random bigger than 0.999

What's the point of the h variable?
h represents the height of the grass can grow each time.

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
Using "-10" because there is a thick line on the bottom, which it is -10. 
height-10-random(h) means we start drawing the grass from y=180 which is height-10, and -random(h) means we are picking  number that not taller than h which is 10.
