# slow-neural-style-gui
## An implementation of slow neural style with Torch by jcjohnson: https://github.com/jcjohnson/fast-neural-style
## GUI by AbsurdePhoton www.absurdephoton.fr. This quick and dirty GUI uses QT
### v1.0 - 2018-01-08

![Screenshot](screenshot-gui.jpg?raw=true)
<br/>

## HISTORY

* v1: simple GUI

<br/>
<br/>

## LICENSE

The present code is under GPL v3 license, that means you can do almost whatever you want
with it!
<br/>
<br/>

## WHY?

slow-neural-style is a stunning piece of code, which can apply a style (e.g. Picasso, Van Gogh, whatever you choose) to your photos. For that, it uses A.I., more precisely convolutional neural networks.
slow-neural-style can be found in the fast-neural-style folder, so whenever you find slow-neural-style or fast-neural-style, it is not a typo!

slow-neural-style is nice, but the command-line is complex. So I wrote a simple GUI to use it!

I'm not an ace of C++ and QT: if you don't find my code pretty never mind, because it WORKS, and that's all I'm asking of it :)
In fact it was my first C++ code with QT... I've done much better since. 

<br/>
<br/>

## WITH WHAT?

Developed using:
* Linux Ubuntu	16.04 - it won't work under Windows because it creates an intermediate shell script
* QT5 + QT Creator 3.5
* you will need a good GPU with as much VRAM as possible (I'm using a nVidia GeForce 1080Ti with 11Gb). The size of the output images is proportional to the amount of available VRAM you have

<br/>
<br/>

## HOW?

### Install:
  * grab jcjohnson's fast-neural-style (https://github.com/jcjohnson/fast-neural-style)
  * install all dependencies: torch, caffe, CUDA, etc
  * make it work using the command-line
  * compile slow-neural-style-gui, copy the executable in fast-neural-style's folder
  * launch and enjoy!

### Using the GUI:
  * help is available in the GUI, with each element's tooltip. Just stay your mouse over an element
  * practice makes better! Try to learn what each parameter does
  * load at least the reference image, one style image
  * click "Run": the "result" frame shows neural-style's text output, error messages are in red. Every n images is displayed
  * you can click "Abort" at any moment if the result looks good to you, or if you want to change something without waiting too long (depending on your hardware, it can take several minutes)

slow-neural-style is faster than jcjohnson's original neural-style implementation - try it, the results can be slightly different! 
   
<br/>
<br/>

## Enjoy!

### AbsurdePhoton
My photographer website ''Photongénique'': www.absurdephoton.fr

