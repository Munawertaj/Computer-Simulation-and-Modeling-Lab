# Problem : Simulation of a pure pursuit problem.

## Problem Statement:

- A fighter aircraft sights an enemy bomber aircraft and flies directly toward it, in order to catch up
  with the bomber and destroy it. The bomber (the target) continues flying (along a specified curve)
  so the fighter (the pursuer) has to change its direction to keep pointed toward the target. We are
  interested in determining the attack course of the fighter and in knowing how long it would
  take for it to catch up with the bomber. Solve this problem under the following conditions.
  You need to plot the whole path of fighter as well as bomber:

- Logic behind the pure pursuit problem of simulation:
  • Bomber Aircraft and a Fighter Aircraft are flying in the same horizontal plane.
  • Fighter aircraft and bomber aircraft both are moving inside the rectangular range.
  • The fighters and bombers have a velocity given, suppose s = 20 (input from screen).
  • The bomber and the fighter path co-ordinate (i.e., its position as a function of time) are randomizing from 1 to 1000.
  • When the distance of the bomber and the fighter is less than 100km, it is assumed that the bomber is shot down or destroyed and if the distance is greater than 900 km, it is assumed that the bomber escaped from sight.
