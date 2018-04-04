# PhysicsFoosball
Will keep track of my progress of particular components of my physics engine for my virtual foosball game.

Project 1: (Released: Sunday, March 18th, 2018)

  Model the movement of a ball in 3D space. Tackle the problem twice. Each time with a different approach
   
     Approach 1: Write the program in .js and use a fullfledged physics engine to model the movements
     
     Approach 2: Write the program in .js but this time don't use any physics libraries,
     write the whole program yourself



Project 2: (Releasing: Sunday, April 8th, 2018)

  Model the movement of a ball with no movement of the ball in the up and down position. Consider the point mass as we
  did in project 1. Also, consider rotational motion of the ball around its' own access.
  
      Approach 1: Write the program in on my own in .js without help of a major physics engine library
      
      Approach 2: Write the program using the CANNON.js physics engine library
      
Physics:

      -> Angular displacement (theta):
      
         theta = theta sub naught + omega sub naught * time + (1/2) * alpha * time^2
      
      -> Angulare velocity (omega):
     
         omega = omega sub naught + alpha * time
         --or--
         omega^2 = omega sub naught ^2 + 2 * alpha *(theta - theta sub naught)
      
      -> Angular acceleration (alpha):
      
         alpha average = change in omega / change in time
      
         
      
      -> Kinetic energy of a rotating object:
          K = (1/2)*I*omega^2 where I is moment of inertia
          
      -> 
      
