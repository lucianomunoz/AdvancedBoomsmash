# Advanced-Boomsmash

First, a "boomsmash" is an OpenGL render that grabs images from the view-port and spits them as fast as it can to the hard drive, to the people that comes from Maya this is known as playblast.

It's specially useful to preview animation when they can't be watched real-time in the viewport itself, so in animation we use it quite a lot, (I try to keep my rigs light, but often is the mix of multiple rigs, and background and such that still crushes performance).<!--more-->

<img class=" size-full wp-image-351 aligncenter" src="https://lollypopmancom.files.wordpress.com/2016/02/2016-02-24-13_48_07-blender_-h__dropbox_raise-project_animaciones_finales_nariz_looch-blend.png" alt="2016-02-24 13_48_07-Blender_ [H__Dropbox_raise project_Animaciones_FINALES_Nariz_Looch.blend].png" width="316" height="308" />

We developed this add-on, with my friend Cristian, and we even though we've been halted for a while, I think it's at a usable stage.

Advanced Boomsmash that sits in the Tools tab in Pose Mode and in the Animation Tab in Object Mode, and it looks to add options to your current openGL preview animation which will make it more confortable when you're going back and for between animation and rendering and such so you dont have to also go back and forth with changing parameters.

*Boomsmash = openGL render.

<span style="text-decoration: underline;"><strong>Features</strong></span>:

Stamp
It turns on stamp only for boomsmash (regardless it's deactivated for regular rendering)

Only render
Turns on only render for the view you're boomsmashing.

Transparency
Gives you a transparent bg (works only if your output supports transparency and there is no background geometry in the shot)

Autoplay
Opens up the player you have set by default with the animation loaded and ready to watch.

Unsimplify
If simplify is on (it probably is if you're trying to animate fast) it will turn it off for the boomsmash so you can see your silhouettes as smooth as they should be.

Use preview range
will boomsmash your preview range only.

Resolution Percentage
it will boomsmash at a percentage of the current render output (just so it renders faster and also you don't have to be going and changing your res back and forth for the actual render output)

Filepath
Will give your file an output path so you don't actually smash your renders if you have done some.

&nbsp;

TO DO:

1.- Output format
To be able to define a different output format from the actual render one, so you can have your scene set up for rendering in image sequence, but that your boomsmash renders in quicktime.

2.- Incremental
If there is a boomsmash already done that it would add a number

3.- Autonaming (based on scene is a good idea)
A default name that will take the name of the scene and be set to create it's BS folder with the movies thrown inside them.

4.- Cancel Boomsmash, being able to hit ESC to cancel the creation of a boomsmash.

5.- Replace the "render opengl animation" button with the boomsmash one so this options just settings you can hide for the most part.

<a href="https://github.com/lucianomunoz/AdvancedBoomsmash" rel="nofollow">DOWNLOAD IT FROM HERE</a>

Hope you guys can make it your own, implement it in your workflow and if someone is willing to add more to it fix, or help implement what's missing it'd be supercool. =)
