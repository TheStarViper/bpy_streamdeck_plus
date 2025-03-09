# bpy_streamdeck_plus

This is for integration of the elgato stream deck+ with blender, I recently wanted to start this project because I currently use linux which is not supported by Elgato's Stream Deck software. I owned a stream deck before moving to linux so it was frustrating not being able to use it. Furthermore, I started to learn blender which has alot of keybinds. This made me want to use the stream deck i had sitting around because since it was the plus version it had dials which would be very useful. So I started looking for linux versions of the software but most did not support the elgato stream deck plus only the standard one and the ones that did had limited functionality. Then, I found a python libary that allows for interacting with the stream deck but nothing else and it supported the dials on the plus version. I decided that I wanted to program my own stream deck software but as a blender plugin because blender plugins have more functionality than the hotkeys, this would allow me more control over blender.

> [!NOTE]
> [Here](https://python-elgato-streamdeck.readthedocs.io/en/stable/examples/plus.html) is a link to the library for the stream deck.

# Macros or full integration?


Blender is full of macros and has hundreds of them, so if I just used those macros and binded them to the elgato stream deck wouldn't we be set?

Technically we would be able to get away with this but I wanted more, and blender just so happens to have a plugin api to create blender plugins in python. This means we can use the stream deck library in the blender plugin!

But this still doesnt give a good idea on how much better this would be, so you can take a look for yourself on how vast the possibilities are with the plugin api right [Here](https://docs.blender.org/api/current/bpy.ops.html)!

# Goals

Now that we have an idea I will list the goals I have for this project:
(all completed will have a green emoji)

- Move object all 3 axes using dials
- Move object all 3 rotational axes using dials
- Scale object all 3 axes using dials
- Move viewport camera using dials
- add modifier button for the ones i use the most
- apply all modifiers (convert to mesh button)
- apply scale button
- apply all transform button
- extrude control with dials
- Duplicate texture (copy texture, new material, paste texture)
- Drop it button (other plugin)
- Delete
- Undo
- Redo
- Render button
- Lock rotation,scale, or movement axes
- move forward backward in timeline (display active frame on stream deck screen)
- play animation
- auto
- create commonly used shapes
- change modes
- spawn bezier curve with geometry node tree applied
- origin point to center,3d cursor,etc
- adjust viewport zoom with dial
- cycle selection modes
- shade smooth
- shade flat
- clear parent
- link materials
- join
- loop cut
- slice
- camera top,bottom,left,right,front,back
- viewport to active camera
- ivy it page (other plugin)
- grass it (other plugin)
- bridge edge loops
- new face
- add path
- hide
- show
- hide from render
- show in render
- select all
- face select
- edge select
- vertice select
- 

> [!TIP]
> Did you know the plural of axis is axes not axises?









# Updates

Sorry nothing here
