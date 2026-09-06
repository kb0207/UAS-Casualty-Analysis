# UAS-Casualty-Analysis
Casualty Analysis using a Rover Guided by UAV


The task says the UAV gives you a segmentation image, where black = obstacle, three greens = traversable terrain, orange = rover start, purple = destination, and casualties are identified by shape + colour.

## Hurdles to solve: 
1. Where can the rover move?
2. Where are the casualties?
3. What type of casualty is each one?
4. Which casualties should the rover visit?
5. In what order?
6. What exact route should it take?
7. What is the score of that route?
8. How long does the route take?
9. Which image has the best score?
10. Which image has the fastest route?

## Rough sketch of how to solve the hurdles and find the most efficient answer
1. Input image
2. Run it through OpenCV
3. Understand pixels
4. Create terrain mask, Detect rover start and end, detect casualties
5. Represent the image in for of a graph
6. Find the shortest path
7. Optimise for casualty visiting order
8. Generate complete rover route
9. Calculate path score, travel distance and travel time
10. Draw route on image
11. Save result
12. Rank all images based on the above parameters





