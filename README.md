# STCoC-Placeables
Adds inventory items that turn into world props when used. 
Currently a modder's resource, but easy to implement manually even if you're not quite a modder. 

It's pretty straightforward. Use the item from your inventory and its prop is placed in the world. 
Currently the props spawn directly on the player's position, which will cause some problems. 

TODO - Basics: 
 * Make props static (disable their physics/ignore collisions with everything but world)
 * Find appropriate model paths for items with faulty ones / Create loose model files for items without ones. 
 * Add dynamic lights to appropriate props
 * Add fire effects to appropriate props
 * Add sound effects to appropriate props
 * Add radio functionality to radios
 * Make it possible to select radiostation for the radio (CoC's scripted context menu?)

TODO - Release: 
 * Adjust item placement position to where actor is looking
 * Adjust item placement rotation to be aligned with actor
 * Add xray condition check to count objects by section name in a SMART
 * Add SMART terrain properties that are active when certain placeables are in SMART

Suggestions: 
 * Add placement preview
