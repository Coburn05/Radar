# Radar
[WORK IN PROGRESS] tracking radar made from 3 C4001 human presence radars

idea is that if I am able to get 3 distance readings from each radar used, then I can solve for the location of the observed object in 3D space relative to the radar.
I want to apply this idea to track things like paper airplanes, and maybe bugs if the radar is able to pick them up.
I went with a static 3-radar aproach as I do not want to use 2 moving radars, where one pans and the other tilts. While this is a workable idea, the math used to get an accurate position
on the object would be complicated and still provide a low resolution when compared to the 3 radar aproach.

this is a graph of the ideal "visual" zone of the radar, where s is the distance between radars: 
https://www.desmos.com/3d/bksvc8zjhk
