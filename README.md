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

What's the point of an object?
An object has its data inside, so learning an object can know more about its elements information, let's say a cup is an object, which a cup has its color, height, and materials, it could be a data. If we are coding a cup, we have to know its informations like this.

What's an example of a range you might use for the map function?
    If my canvas width is 0-600, and the color range is 0-255, using the map function can change my background color base on my mouse X, so it could looks like this function r=map(mouseX,0,600,0,255)
    
What line of code would give me a random year in the last century?
var x= random(1900,2000)
