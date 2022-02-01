# __LGNN (Lagrangian Graph Neural Network)__

## __How to run__
Run all spcripts from scripts directory.

__Requirement__

numpy-1.20.3, jax-0.2.24, jax-md-0.1.20, jaxlib-0.1.73, jraph-0.0.1.dev0

## __Visualization of trajectories__

### __Spring System__

1. __5 balls connected with springs__

![spring](/assets/gifs/5_spring.gif)


### __Hybrid Systems__
Seperately trained LGNN for spring system and pendulum system were used to simulate the hybrid system. Here, gravitational force applied on the balls connected with spring were trained on pendulum system.

1. __Hybrid system (two balls connected to double pendulum using sperings)__

![spring](/assets/gifs/hybrid_no_force.gif)


2. __Hybrid system (two balls connected to double pendulum using sperings and a force of 10N in horizontal direction is applied to second bob.)__

![spring](/assets/gifs/hybrid_force_10x.gif)