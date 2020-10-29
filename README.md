# GodotRetro

![png](https://github.com/Ahopness/GodotRetro/blob/main/Fotage/icon.png?raw=true)

Version 1.0



## About

**Godot Retro** is a shader pack for godot, with various ports of shades from *ShaderToy*, *Unity* and The *Book Of Shaders*. 



## License

Godot Retro is free to use and modify by everybody, *however*, the name of the developer and porter(me) of the used shader must be credited.



## Shaders

### PSX

*A modified psx shader.*

![gif](https://i.imgur.com/V9wAYKK.mp4)


### COLOR PRECISION

*A color precision screen space shader.*

![gif](https://i.imgur.com/jTmPIQA.mp4)


### BLACK & WHITE

*A B&W screen space shader.* 

![gif](https://i.imgur.com/YspHvsh.mp4)


### GRAIN

*A film grain screen space shader.* 

![gif](https://i.imgur.com/2SiUVLa.mp4)


### TV

*A TV screen space shader.* 

![gif](https://i.imgur.com/tSlFZAl.mp4)


### VHS

*A VHS screen space shader.* 

![gif](https://i.imgur.com/y7XfFGH.mp4)


### VHS Glitch

*A VHS Glitch screen space shader.* 

![gif](https://i.imgur.com/r3bqmaQ.mp4)


### VHS Pause

*A VHS Pause screen space shader.*

![gif](https://i.imgur.com/WtLWDMM.mp4)


### VHS Simple Glitch

*A VHS Simple Glitch screen space shader.*

![gif](https://i.imgur.com/ePzJpiD.mp4)



## Instalation

**To use the shaders you gotta** :

1. Copy the _GodotRetro_ folder to your project (can be anywhere)


***For normal shader*** :


2. Just add the shader script to a shader material.

***For screen space shaders*** :

2. Add the shader on a TextureRect with the _white.png_ as texture.


**Done!** Have fun!



## DEMO

Free easy to lean demo is available with the pack.


**Demo Controls**:

W = Foward.

S = Backwards.

A = Turn left.

D = Turn right.

Q = Walk left.

E = Walk right.

Shift = Run.

1 = change shader on layer 1.

2 = change shader on layer 2.



### DISCLAMER :

 - To use 2+ shaders at the same time, you gotta use a *BackBufferCopy* set as *Viewport* for each effect.

 - For UI, be sure to set it above the shaders for then to be aplied for more imersion.



## Features

 - **9** easy to use godot shaders
 
 - **Frequentily updated**

 - Well done **demo project**



## Limitations

Unfortnetly, some shaders arent 100% perfect.

 - The grain shader dont have a size slider.
 
 - Some shaders (*1*) dont have sliders to make the best experience.

 - The Color Precission shader's dithering dont work because of Godot's limitation.

 
 #All the limitations should be fixed with time and from help from contributors.



## TODO

 - Add more options in some shaders.

 - Add dithering shader inside or outside the color precission shader.

 - Add better film grain.

 - Finish and solve bugs on the PSX shaders.



## Credits 

Shaders ported by : **Ahopness (@ahopness)**


B&W shader made by : **demofox (ShaderToy)**

Color precission shader made by : **abelcamarena (ShaderToy)**

Grain shader made by : **juniorxsound (ShaderToy)**

TV shader made by : **ehj1 (ShaderToy)**

VHS shader made by : **FMS_Cat (ShaderToy)**

VHS glitch shader made by : **keijiro (GitHub)**

VHS pause shader made by : **caaaaaaarter (ShaderToy)**

VHS simple glitch pause shader made by : **Gaktan (ShaderToy)**
