# Swarm-Flocking

## Project Description

[Reynolds Flocking](https://www.red3d.com/cwr/boids/) is a computer model invented by Craig Reynolds in 1986. It aims for simulating the coordinated motion of large number of animals such as bird flocks and fish schools.

The implementation is based on this paper:
Hauert, Sabine, et al. "Reynolds flocking in reality with fixed-wing robots: communication range vs. maximum turning rate." 2011 IEEE/RSJ International Conference on Intelligent Robots and Systems. IEEE, 2011.

The Coachswarm simulation is provided by Professor Michael Rubenstein at Northwestern University.

Since this is a class project, the python code cannot be made public. If you are interested, please contact me for more details.

## Approach

Each agent follows a simple behavior to interact with its neighbors. The behavior is defined by four steering vectors:

1. Alignment: Mean velocity of all neighbors
2. Cohesion: Center of mass of all neighbors
3. Seperation: Repulsive vector that avoids being too closed to the neighbors
4. Migration: A vector that points to the common goal (In the demo, it is the center)

## Full Demo Video:

The robots will be randomly placed at the beginning. They will soon group together and move around the center. At the last ten seconds of the video, the flock converges to a circular motion around the migration point.
  
[Demo Video on Youtube](https://youtu.be/z49zlZkwjSs)
