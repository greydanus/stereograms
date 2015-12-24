Stereograms
=======
Code for playing with random dot stereograms. Originally built as a supplement to my article *Depth perception: more than meets the eye*

Description
-----------
A set of ipython notebooks for making autostereogram demos and generally exploring their properties. For a good intro to stereograms, check out [Wikipedia](https://en.wikipedia.org/wiki/Autostereogram) or Gary Beene's [personal website](http://www.garybeene.com/stereo/rds-over.htm)

The notebook which takes depth masks was inspired by code from [synesthesiam](https://github.com/synesthesiam/magicpy)

I emphasize that this is a work in progress. I am actively experimenting with the code so that I can better understand how stereograms work. You should too. If you have any questions, contact me at sam.17@dartmouth.edu

Dependencies
--------
* All code is written in python 2.7. You will need:
 * Numpy
 * Matplotlib

The project should port pretty easily to python 3 as long as you change the "xrange" keywords to "range" and other such minor changes

Examples
--------
The "rds simple" notebook creates basic dual image autostereograms like this:

* Converge or diverge the eyes so as to see a triplet of three red dots. Clear any blurriness but maintain the triplet to see a rectangle emerge from the background dots in vivid 3D. *
![shark.png](https://raw.github.com/samjgrey3/stereograms/master/examples/static_dual_example.png)

The "rds depth mask" notebook creates autostereograms like this:

* Converge or diverge the eyes so as to see a triplet of three black dots. Clear any blurriness but maintain the triplet to see a shark emerge from the background dots in vivid 3D. *
![shark.png](https://raw.github.com/samjgrey3/stereograms/master/examples/static_shark_example.png)
