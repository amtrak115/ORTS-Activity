MSTS 89' Autorack Pack Part 7 (Add-on pak)

Contained within the pack are a further 10  completely different 89' Autoraks both Bi-level and Tri-level,
Part 7  Comprises 2 x ATSF, 1 x CRR, 1 x DRGW, 1 x ICG, 4 x SLSF, and 1 x WP.

to use and place the resulting folder from unzipping "Autoracks_Jeff_A" into the Trains/Trainset folder
within MSTS, create a consist using the MSTS editor, Conbuilder or your favourite utility.

If you have downloaded any of the other parts of this set (currently 7 parts including this one) they will
all share the same folder and therefore the truck ace files will want to overwrite any previous ones, that 
is ok. in some instances,( depends on unzipping program and various PC configurations), you may have to 
manually copy the contents of each part into the one main one.
------------------------------------------------------------------------------------------------------------

BLURRY TEXTURES
In view of the mixed comments recieved on previous addons to this set regarding blurry textures that some
users are experiencing, I have in set 6 and  this set returned the texture settings in the shape file to the
MSTS std of -3, this should cure the blurriness experienced by those who do not have Anti Aliasing and Ansitropic
Filtering turned on within their graphics card settings, this may also bring back the moire patterns that
have plagued so many autorack repaints in the past and for which reason i made the changes in the first 
place. 

If you have Ansiotropic Filtering and Anti Aliasing turned on and you wish to lessen or rid the
racks of the moire patterns then do the following (experienced users only)

decompress the shape file and open it in word pad or any other unicode aware editor, scroll down and find this section

	images ( 2 
		image ( Truck5-JA.ace ) 
		image ( PW_104320.ace ) 
	) 
	textures ( 2 
		texture ( 0 0 -3 FF000000 ) 
		texture ( 1 0 -3 FF000000 ) 


alter the second texture parameters to read thus -2 instead of -3


	textures ( 2 
		texture ( 0 0 -3 FF000000 ) 
		texture ( 1 0 -2 FF000000 ) 

recompress the shape file and try in the sim, some of you may be able to take that down to -1 but will
depend on the PC setup.

the ACE file being compressed and saved in the DXTI format is part of the moire removal or limiting 
process, do not try to alter and resave in the DTXI format again as each time the ace file is saved
in that format it will get worse and the quality will degrade, saving in the DXTI format is a one off
process, it works if you only save once from an original hi-res source as the initial reduction in quality
is small, it however gets far worse if saved more than once, i always save the hi-res sources and renumber
or rework any new cars from those, basically what i am trying to say is that the blurry textures some
were getting was not due to the ace file being saved in the DXTI format it was a dirsct result of the 
changes to the shape file for users not using the Anti Aliasing and Ansiotropic filtering features of
their graphics cards.


------------------------------------------------------------------------------------------------------------
CREDITS/COPYRIGHTS:

Jeff Auberpine: 3D Shapes and original textures (this set ICG, WP & ATSF #875326 units)
Bernard Grant: remaining Renumbers, Set Creation and Uploading

This pack is freeware and not to be used for commercial purposes under any circumstances. reskinning is allowed
as long as Jeff or myself are asked before upoloading anywhere.

by Jeff Auberpine   railbass6@yahoo.com &
Bernard Grant (burgerbern) mltd_file_librarian@ntlworld.com