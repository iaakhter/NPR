#Itrat Ahmed Akhter

I decided to extend my class project and implement some non photorealistic(npr) effects on 
images using javascript and html. To run the index html file, use the most updated version
of firefox/chrome. Click on Browse, select an image file from 'img' folder and then 
click on 'Click to See Effect' link to view the image. I have implemented 5 npr techniques
and the user can choose the effect that he/she wants to view from the gui controls
on the top right corner of the page. Click on 'open controls' on the top right to view
the different npr options.Each npr techniqe also has variables attached to it that the
user can control.
The npr techniques are as follows:


Delaunay Triangulation:
Implements delaunay triangulation (using Bower-Watson algorithm). The variable that the
user can control is the delaunNumVertices and increasing it increases the number of
triangles on the picture.

Voronoi Diagram:
Implements pixelation of an image using a voronoi diagram implemented using Euclidean
distance metric. The variable that the user can control is called voronoiBlockSize and
it defines the size of each pixel.

Blur:
Implements distortion blur of an image. The variable that the user can control is
called distortionBlur and increasing it increases the blur effect.

Oil Paint:
Implements the oil paint looking effect. The variable that the user can control is the
filterOil and increasing it increases the oil paint effect.

Cartoon:
Implements gradient based edge detection on oil paint filter thus giving a cartoony
effect. The variables that the user can control are filterOil and cartoonThreshold.
Increasing filterOil increases oil paint effect. Decreasing cartoonThreshold increases
dark edges. 

The user must have only one option selected to see the effect of an npr. Selecting more
than one option does not allow the user to see any npr effects.

To implement all the effects, I took help from the following webpage:
http://softwarebydefault.com/

For delaunay triangulation, I used the Bower-Watson algorithm. The algorithm to calculate
the super triangle for the Bower-Watson algorithm is taken from github:
https://github.com/ironwallaby/delaunay/blob/master/delaunay.js

I would also like to thank Bilal Ahmad (Colby College Class of 2015) for being my partner
on one of the projects from which I took elements to extend this project.

Also, some of the effects take longer to run than the others.
