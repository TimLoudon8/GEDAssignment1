# GEDAssignment1

In the first tutorial, we set up the character, basic movement and a looping animation.  We used action maps to create this 
movement and input actions to get key presses.

In the second tutorial, we created a shooting class, an editor camera, jumping, and the ability to collect coins.  While this is good,
the editor cam's function to place objects only works once and places the object at the origin.

I have changed the collider on the player from capsule to box to minimize falling over, attempted to despawn bullets after they are fired,
movement now works with a singleton and coins no longer have a collider and are treated as a trigger.