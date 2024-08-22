This is kind of a todo list for us, devs

- Have a good storyline, that will improve as the development of the game goes on
- Think about the functionnalities, the experience, how build will go, game in 3d
    - Build: Shapez 2 and Dyson sphere program are good at this
    - Machines: Different sizes (start: millimeters, end game: machines that operate at planet scale, or bigger)
See how other games implement x or y functionnality
- Start coding ! Using Unreal engine, blueprints and some C++.
I would also like some Rust, but we will see how it goes...
## Coding
- Familiarise with Unreal Engine
- Make a hashmap for world map (optimisation later on pls)
- Make some update functions for the machines,
- Quickly make assets for machines & all, polishing later
- Quickly make ui, for selecting map, multiplayer, game settings ...

- Make the game multiplayer

- Optimise the game, so that it runs blazingly fast (like if we made it in Rust)
### Optimisations
Some optimisations that we thought of during dev time
Using some sort of Sparse Octree for storing the map, and maybe also an array with all machines.
Some machines might not need to update every tick
Try to get the average production of a part of the factory, and stops updating the part when player far away, then get last updated time, and multiply by average production (I can easily see players cheating using this, so... Needs to be done with precaution)

- Polish assets, learn Blender or contact someone that is good at drawing