# 2026-Fishes Aquarium Assignment

An aquarium scene built using PixiJS.

## My Coding Strategy

* **Separated Lanes:** To stop the fish from crashing into each other, I gave each one its own zone (top, middle, and bottom) so they never overlap.
* **Fish movement:** I put each fish in a container with its own vx and vy speeds so they can swim across the screen independently.
* **Wall Bouncing:** When a fish hits a wall, its speed reverses  and its scale flips so it instantly turns around and faces forward. 
* **Buttons:** To make one of the fishes to change color and draggable. 
* **Animations:** Extending the animation to handle scale,rotation, tint, and alpha. Also, I made fish 1 to idly bob around and when clicked it swims up to the surface and then swims back down in its bobbing state. I also made fish 2 to swim over to where i tap on the glass. 


## Citing my Assets

* **Fishes Asset:** [Vecteezy]
* **Background Ocean Texture (`bg.png`):** [https://unsplash.com/photos/clear-blue-body-of-water-XexawgzYOBc]
* **Plant  (`plant.jpg`):** [https://www.vecteezy.com/png/58187841-fresh-vibrant-seaweed-clipart-for-underwater-design-projects]
