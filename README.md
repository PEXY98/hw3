1. What code draws the blades of grass?
   line(x, height-10, x+random(-10, 10), height-10-random(h));

2. What code makes the "lawnmower" come by? How often does it come by?
   if (random() > 0.999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
  }
  
3. What's the point of the h variable?
   let the grass grows as the speen of h = h + 3
   
4. What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
   So the grass doesnt grow from 10 since var h = 10 
