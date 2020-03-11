nukemod for ksp
i went there

current version: 6ish
aka r5

warning: this readme file may cause cancer. side effects include: unquenchable bloodlust, self destructive tendencies, rectal bleeding, funny colored urine, intense sexual attraction to spiny life forms (like cacti, porcupines, hedgehogs, etc), and hypergolic flatuence that detonates when exposed to air. use at your own risk.

changelog:
beta 1 - initial release
beta 2 - fixed normal maps for long and short tanks, and the nosecone
		 mpd thruster overheat animation looks better now
		 mpd thruster now produces less heat and is less prone to self destruction
		 mpd thruster weight reduction from 1.2 to 0.8
		 gimbal ranges reduced on mpd thruster and gimballed engine to compensate for bang bang control
gamma 3 - moar parts
		  a lot more parts
		  some of them even work
		  new resources
		  atmospheric bits
		  some ships
		  and a cockpit
		  also no longer calling it a beta since i dont need a reason
		  this version requires at least ksp v.18
delta 4 - 0.20 compatibility (now uses new mod heirarchy)
		  all textures are now png
		  NEW! structural lattice construction kit
		  some parts now come in a larger sizes
		  better colliders for parts that had bad colliders (like the cockpit and the tail boom)
		  depricated arrrghohn, all hall thrusters and mpd engines now use xenon
		  resized fuel tanks to more strict specifications to make them compatible with the new lattice elements
		  rebalenced some parts (mono tank is a lot less useless now)
		  atmospheric vtol engine can now be throttled more quickly
		  *known issue* 0.20 broke the sound effects so that badass mpd thruster sound doesnt work
fred 5  - brought up to 0.23.5 (hincefourth releases will be named after pet rocks owned by my cats).
		  all textures are now tga. squad, for the wrath of lucifer, use sane texture formats (like dxt1). 
		  dublicate textures annexed!
		  tech tree support (i think, i havent actually tested it).
		  replaced bleed air and bleed gas with bleed system pressure, bleed thrusters are now interchangeable.
		  reworked mpd thrusters, should now work more sanely (but still power hungry).
		  all part cfgs now use MODEL{} and NODE{} instead of the old skool way.
		  new particle effects. the mpd engines and arcjet (and i want to do the hall thrusters if i figure out how) now have exhaust effects.
		  sounds work now and there are more of them (i apologize in advance for my horrible sound engineering skills).
		  various balance tweaks.
		  experimental: ducted fan and vtol engine now have working rotors (powered by firespitter).
		  experimental: intakes may accept atmosphere with or without oxygen and produce appropriate resources (though i need to find a better way to do this).
		  new parts:	small glider wing
						small delta wing (with fuel tanks)
						solar wings (with batteries and solar panels)
						small canard
						small tail fin
						small aerodynamic pylon
						dual mode (chem/electric) arcjet
						electric ducted fan
6ish	- the quasi-maintained version that i use in my ksp installs. its got unresolved bugs due to not being maintained very well. also im tired of naming things.
		  some of the new parts i teased about some years ago are finally in. i gave them crude textures and they actually didnt look too bad.
		  these parts include the micro girders and engines. 
		  some experimental stuff i forgot as a result to my state leegilizig marijuana.
		  added module manager support somewhere so it should now gracefully handle having tweakscale and firespitter installed, or not.
		  seeing about kcan support because maintaining mods is hard. 
		

license: 
the nihilist's license terms are follows:



that concludes the license terms. i dont make mods because i give a fuck how the world wants to self organized nor will i be a part of it. its free stuff, enjoy it.
ok the license is really public domain, its really all the same. pirate this mod. 

im going to abandon this stuff one day so i figure id cut out the middle man and just put it in public domain where it belongs. but plese dont be a dick about it (see 'psychotic rant' below). 
dont claim it as your own. i would like the common curtousy of being in the credits. this is what the profesionals do. this is the kind of shit that made me leave the freespace community.

installation:
move the 'Nuke' directory into your KSP_Root/GameData/ folder. 
optionally you may copy the 'Ships' directory to KSP_Root, if you want to use my shoddy craft files. at least you can do that if i get around to making new craft files,
i lost the old ones to a drunken rage.

description: 
this pack contains the following parts, none of them use any plugins yet 
*note* was too lazy to update this so some stuff got renamed

part									description
--------------------------------------------------------------------------------
RD-L-13 Light Radial Decoupler			your typical radial decoupler doesnt really do anything new
ADF-R-05 Radial Adapter					for connecting half meter tanks and engines to the side of things, cross feed capable
NC-RCS-05 Rcs Nosecone					a half meter nose cone for yaw and pitch control (doesnt do roll yet, il look into fixing that)
RFT-05 Rcs Tank							a small half meter rcs tank, doesnt hold much fuel.
LFT-05-S Liquid Fuel Tank				a small half meter tank that does what tanks do
LFT-05-L Liquid Fuel Tank				bigger version of the above
LFE-05-F Fixed Engine					a powerful half meter engine
LFE-05-G Gimballed Engine				a less powerful engine with a wide gimbal angle
MPDT-RTG-1337 MPD Thruster				a weak but highly effitient thruster for upper stages (i want to make this thing require power via a plugin once i figure out how)
ADF-05-1 Adapter						lets you connect half meter parts to meter parts and vise versa (crossfeed capable)
ADF-1-05-Q Quad Coupler					connects four half meter engines to a one meter tank (crossfeeds down only)
CPLR-19 Undeviginti Coupler				for those that dont speak latin this lets you connect 19 one meter things under it and a thing above it. dont hurt yourself.
ARGT-05-1750 Arrrghon Tank				a small tank of pirate gas, useful for electric engines
Bat-05-04k Battery						a magic tank full of zap. dont let the blue smoke out or you will ruin it
ACB-05-1-2 Bicoupler					stick two things to one thing, awesomesauce!
CPT_M1_328_G Cockpit					nice cramped little aircraft cockpit, its as light as it is sexy
EP-05 Engine Pylon						lets you hang engine and intakes from things
ACTI-05-1-3 Inline Tricoupler			stick three things to one thing! now were talking!
JE-05 Jet Engine						inhales air, exhales fire. what more could a kerbal want
LJFT-05 Jet Fuel Tank					a hald meter place to put jet fuel
ACTR-05-1-3 Inline Tricoupler			stick three things to one thing. wait, didnt we have one of those already? but this one keeps em in line you say? hell yeah!
SCI-05 Shock Cone Intake				a pointy thing for poking holes in the atmosphere, watch your eyes around that thing
HEX-05-06 Station Hub					stick 5 things to one thing, ok now this is just getting rediculous
TB-05 Tail Boom							take a look at the tail on that gal. not that you kerbals know what a gal is.
JEVI-05 Vtol Jet Engine					a jet engine that is pointed down instad of back, creates bleed air for thrusters while its running too!
BAT-015-T Bleed Air Thruster			a compressed bair thruster for stabilizing your vtol
REV-05 Vtol Rocket Engine				a rocket engine that does the same thing as the jet engine pointing down, creates bleed exause while its running.
BETQ-015 Bleed Exaust Thruster			a bleed exaust thruster, no not a bleed air thruster, its something entirely different!
HET-10-L Hall Thruster					an electric-pirate gas thruster slow but doesnt waste fuel
HET-10-L Hall Thruster Quad				four times the electric thrust for the price of one
MPDT-D-2674 Dual MPD Thruster			here is a super efficient engine for deep space craft. its also a power hungry beast, bring along no fewer that 50 solar panels
ARGT-1-19_6k Arrrghon Tank				enough pirate gas to get you to jool and back. be advised, this much pirate gas is heavy and will make your ship slow

STRL-05-025 Tiny Structural Lattice		0.25m lattice peice
STRL-05-05 Small Structural Lattice		0.5m same as above but bigger
STRL-05-10 Medium Structural Lattice	1m same as above but bigger
STRL-05-20 Large Structural Lattice		2m same as above but bigger
STRL-05-40 Huge Structural Lattice		4m same as above but bigger
STRL-05-B-1-1 Bent Structural Lattice	same as above but bigger, lol, just kidding, its a 1m radius quarter circle (i even had to use math to make it line up correctly)
STRL-05-0175 Structural Lattice Spacer	0.175m spacer for offsetting station hubs
STRL_D-05-0125 Automatic Coupler		0.125m dock, for sticking together bits of lattice that would other wise be unconnected given the tree structure of the craft. 

model numbers ommited to lazy to copy	small glider wing
										small delta wing (with fuel tanks)
										solar wings (with batteries and solar panels)
										small canard
										small tail fin
										small aerodynamic pylon
										dual mode (chem/electric) arcjet
										electric ducted fan
										
and more stuff that i didnt bother to document

ships									description
--------------------------------------------------------
MicroFlier								a small jet, light but not very stable
MicroGlider								a small glider, use the srbs to get some altitude, and glide around for awhile, its hard to get back down, with its epic glide slope and all
MicroSpacePlane							a small space plane capable of reaching orbit, easier to fly than the old one, but no mpd so no duna for you.
MicroVtol								a small (seems we got a theme going on here), this is a ship that can take off vertically. its hard to control (do yourself a favor and stick a mechjeb pod on it, really)
Ultralight Vtol							a cute litle vtol, can fly autonomously or can seat 2 kerbals (but not one)
Ultralight Vtol (zero atmo edition)		same as this ^ but with rockets instead of turbines
Some Kind Of Monster					c-c-c-c-c-c-c-c-combobreaker! A ship to show off the new lattice system, has a lot mpd thrusters, and a lot of solar panels. though probibly not enough (todo: nuclear reactor). 

*note* didnt feel like updating the star serpant, too many batteries!

notes:
i use the nuke_ prefix for all my part folders, at least i used to, now i just put everything inder GameData/Nuke
i use 7zip because it offends those who shouldnt be allowed to use computers or rather i dont because spaceport dont support it, i might use it again if i go 
back to google drive. ha! really its better than zip, just be glad its not a tarball. 

about the mod:
i started this pack around ksp .13, but discontinued work until i had the cash to buy the game. it mostly contains half meter parts which i kinda thought were
lacking in the mod packs that were out at the time. recently started adding normal maps and converting to the new mu format, thowing in some new parts here
and there. the only part that isnt normal mapped is the Undeviginti Coupler, for which i seem to have lost the source textures, so i couldnt remove baked in 
highlights and replace it with dynamic higlights. i may redo this texture as it kinda looks bland without normal maps. disreguard this paragraph its really old. 

there may be some issues with balence. initially i estimated tank capacity and engine thrust by examining stock parts, and then tweaked it with the ikao calculator
but it seems that balence guidelines are sketchy at best and not well defined. so i will tweak things for balence when i get better guidlines. 

ive had some issue with connecting the radial decoupler and the radial adapter to some of the stock parts, ive tweaked it abit but it may still be wonky.

after the initial and subsequent fixup beta releases the game got updated again and broke everything. instead of just fixing all the parts and rebalencing it, i
more than doubled the number of parts. while the new parts dont have cool stuff like normal maps (this really isnt an issue because noone liked my normal maps 
anyway), there are a lot of them. after getting them modeled, textured, unityed, part moduled, fixed, broken, and fixed again, here they are, in their
buggy glory. 

ive yet to come up with a name for the mod pack. i guess i could use nukemod, after all i call all my other mods that. im supprised people arent confused yet.
ive considered making a bunch of useful advertising pics to get people interested in my mod. i tell you back in my day we didnt need no advertising to download
every mod there was. we clogged our 56k modems with mod downloads, we could play em faster than we could download em. these days all theese a.d.d whipersnappers
with their 50 megabit internet connections, energy drinks, and violence free education systems wont touch one byte of mod content, without being convinced they
are not wasting their time even reading about it. whatever happened to those days of hex editing new bad guys into games that only had 2 and a half dimentions?

wait what did i loose track again? anyway as i was saying my mod has no name, so you can call it nukemod if you want, or you can call it that mod pack with the
dinky parts, you can call it fred for all i care. 

i updated my mod but didnt want to throw away good material so i left all the stuff up there so you can read it if you are really desperate for something to do. 
frankly most of it is bullshit and not worth your time. but its full of really old information and will probibly give you cancer if you printed it out and
smoked it. 

future plans:
up till now if i needed a part rather than spending hours browsing for a mod that did what i want, id instead spend hours making those very parts. it seems to 
have worked for now. the future may have me make some more parts, there are still things i want. like open cockpits and better power supplies. maybe even write
code for features like fps interiors, centrifuges, and intakes that know what they are breathing. ksp is not really a high priority, its fallend behind my 
hardware projects in terms personal interest. and i also have games like minecraft and mechwarrior online whoring up all my time. and thats when i can find time
and provided im not stoned at the time. i have a lot of cats too so they distract me. im going to add this to kcan and maybe il do periodic updates, which is 
really just me adding to this horrendeous tome and dropping the zip on my google drive. 

psycotic rant (reading this will cause cancer):
if i wanted to speak legalese i woulda gone to law school and wouldn't have had time to make this mod. you use it you credit me! i cant believe in a world 
where you need a fucking licens just to get people to pay you the common fucking courtesy of citing you as their source when they derive shit from your crap.
you did this in colledge you would get expelled. its public domain now, but dont be a dick about it. if you use my stuff its nice to have my name in your
credits. hell even disney (who makes a fortune revisioning public domain works) does this. and these are the same people who keep pushing copywrite periods
towards infinity, ensuring nothing ends up public domain. and if hippocrites like disney can credit creators of public domain works whom they base their shitty
movies off of, you can too. proove that you are better than the mouse! the alternative was a "hunt you down and kill you if you did something i dont like" clause, 
but i thought it wouldnt fly too well in the ksp community. not like it doesnt always apply though. support anarchy (or at least my global empire)! legalize 
murder! tear down licensing infrastructure, commit acts of violence against copywrite organizations. burn down the patent office. line the streets with the
impaled corpses of copywrite lawyers. vivisect the rich copywrite holders who piss all over the public domain. join your local pirate party and steal all the
things. ok that wasnt part of the licens just so you know, public domain was it. i dont belive in intellectual property. you cant really call it intellectual 
anyway, i was stoned when i made most of it. i dont own anything anyway. both concepts are alient to me. this tldr paragraph is also public domain btw. im on
new meds. 

about nuke:
nuke is kind of a hermit who can model, texture, script, program (c/++, lua), hack, engineer, design electronics, build robots and make a mean meatloaf. he is
an old time modder and has moded the following games: descent2, quake, quake2, freespace 2, freelancer, and now ksp. however he rarely releases anything, so
be honored that he chose ksp and actually released a beta. he is also a raving lunatic and plans to vaporise the earth in thermonuclear hellfire. nuke does not
use the internet so dont try to contact him. he wont ask for money but he will drink all your booze if you let him near your liquor cabinet. dont let him near
your mom either, he likes mature fat women. he also likes cats.

   ^-^     
  >'.'< \  
  |\v/|  ) 
 ("d b")_/  
meow, im a cat (at least im a cat if you are using a monospace font, otherwise im just a jumble of programming symbols, vs, bs, and ds)

*readme only contains 27% new content and should not be taken internally.

**hey at least this readme was a better read than a linux man page. 