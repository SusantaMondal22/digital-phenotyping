##The palette

This is how the palette looks (palette.jpg), what I am to do is:
1. Make a rule how to recognize it.
2. Recognize it.
3. Distort it and recognize it.
4. Print it and recognize it.

###june the 9th res:
The machine now knows how to kill background and white area.

##june the 14th res:
The machine now knows how to get an avg colour of the small piece of other 4 areas (see the example: example.png).
Input: pic of a certain pattern. Output: 4 3-tuples with average RGB values of an area.

##june the 14th res:
1) New pattern to recognize (piece.jpg).
2) Geometrical algorithm of recognition (measurment of distances between centres).
3) Yet to test on distortions.

##june the 16th res:
Piece pattern was successfully recognized -- it was a spheric vaccum version created by python means with pure digital colours.

Now, with testing of distorted variants, an issue has occured -- after rotation of an array all the coordinates get shifted and mask is created poorly. 
Somehow, I need to rearrange coordinates after rotation. (Biased mask creation see on biased.png) 
