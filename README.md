I put this repository together as a small side project which explores the distortions introduced by the Web Mercator map projection and their impact on long distance hiking trails. Thru Hikes represent one of the few modes of transportation at a large enough scale where 1) distortions impact the traveler, 2) the mode of transportation is slow and labor intensive and 3) Web Mercator is the standard projection used by travelers. Included in the main notebook are figures which I've used for a writeup of this analysis hosted on my website, [linked here](https:jhdorsett.github.io/personal/trail.html). 

The user can use the included environment.yml to setup the project using conda:

```conda env create --file=environment.yml```

And read in additional trails and map projections. 