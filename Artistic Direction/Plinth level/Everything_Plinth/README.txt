BACKGROUND.png : 	A static background, meant to represent the sky. Intend to reuse on menu page as well.

TOKEN.png : 		The token for the level, meant to be placed in the higher of the two underground tunnels. Should bob up and down slightly if possible; if it would be easier to have it rotating we can do that as well.

PLINTH_REAL.svg : 	The editable vector file with all information relevant to the level. 

Plinth Layers:		Meant to be layered on top of each other, with PLINTH_BACKGROUND in the back, PLINTH_GROUND in the middle, and PLINTH_TOP on top. All these images have the same size, so it they're all scaled the same, they should line up perfectly. Per the SVG file, a milimeter is a pixel-art pixel, and the total level is 778.000 mm wide by 425.000 mm tall (Note: This was built for a 75 mm by 50 mm screen). The images were exported at 3000px by 1639px (computer pixels), but those can be rescaled if they need to either be higher quality or take up less storage space. 

	- PLINTH_BACKGROUND.png: 	A background that moves with the level. Mostly just the bricks and showing that's the terrace in the plinth is a real structure that exists, even if only certain parts of it can be interacted with. 

	- PLINTH_GROUND.png: 		This is the layer the player actually interacts with, climbs, etc.

	- (Cat sprite goes here, in terms of layers)

	- PLINTH_TOP.png:		This is the layer that goes on top of the PLINTH_GROUND layer that gives the level life. It has shading, grass/moss(?) that the player can't interact with, it's purely an aesthetic layer. 

	- (TENITIVE) It would be nice to have an animation later on top of this: some mist moving around, birds flying in the background, grass swaying in the wind, etc.

CAT WALKING SPITES:	Frames of the cat walking. They are all 16mm x 11mm. For both Left and Right, 1 is the rest position, 2 and 3 are walking positions (alternate), and 4 is a transition frame between 1 and 3. 
