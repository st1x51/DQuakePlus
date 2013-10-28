==========
DQuakePlus
==========
Fork of DQuake>>http://sourceforge.net/projects/pdquake/ 
Original DQuake by Crow_Bar. 
Used parts from:  
QRack by R00K,   
JoeQuake by Joseph,    
FitzQuake by John Fitzburg,  
Kurok by mdave,    
FuhQuake by fuh a norai,   
FteQuake by Spike,   
and DarkPlaces by Lord Havok!   

Features:
- Q1BSP,HLBSP
- MDL, MD2, MD3
- Halflife / CS1.6 Modelformat(without bone controll)
- QMB and Quake 3 Particles
- External Textures (bmp,tga,png,pcx)
- spr,spr32 for sprites
- decals
- skybox from kurok
- color lightmaps (from kurok / and for hlbsp);
- fog

==========
How to compile
==========
1)download cygwin>http://quake-1.com/cache/cygwin.rar

2)Extract folder on C://

3)Go in to cygwin folder and launch .bat file

4)Type "cd" and path to psp folder with make files,like a "cd dquakeplus/psp"

5)To compile SLIM EBOOT type "make -f  makeslim install"

  To compile PHAT EBOOT type "make -f makephat install"
  
6)Profit
==========
Transparency
==========
use prefix "{" for transparency like in HalfLife and like Kurok(see kurok.wad for example)  
R:159 G:091 B:083 for transparent textures like a Kurok
R:0 G:0 B:255 for transparent textures like a Half Life
little example:
{mytexture
