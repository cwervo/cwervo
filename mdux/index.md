## MDUX

**M**ulti**D**imensional **User** **Experience**

You might imagine a [latent space](../all-our-latent-spaces/) of all possible interfaces. Digital & physical. What could that look like?

Well, you must define a point to talk about a latent space.

# So, let's establish `P = n`

`n` here is really any value. "heat of the water" & your bathtub temperature is a 1D UI over heat. You can think about that line of interaction too! If there's a "coldest" & "hottest" side then you're dragging the `P` of your interface from `0` to `1` (`0` = low energy w/in the water, `1` = high energy).

### What's a `P` of `2`?

`P2` is any value that has two associated coordinates. So you're trackpad is a `P2` system, it's literally a bound Cartesian Plane.

Wait, so what's a mouse? Well it's a `P2` vector searching through `X` & `Y` on your screen. You can easily draw a map between the mouse's idea of `0,0` & your screen. In fact your computer is doing it (if you're on a Mac I think [Core OS](https://developer.apple.com/library/archive/documentation/MacOSX/Conceptual/OSX_Technology_Overview/SystemTechnology/SystemTechnology.html) is doing it?) at least 30 times a second.

## P3

Pitch, yaw, roll controllers for helictopters. A `P2` or `P3` interface is really hard to control in dangerous situations (which is why the trend of giant touch screens in cars is so scary, because you don't have motor memory for flat surfaces) so [helicopter controls](https://en.wikipedia.org/wiki/Helicopter_flight_controls) seem to actually work by building `P1` vectors. If I understand that page correctly (based on an afternoon of reading), we might say:

- the _cyclic_ is is a `P2` controller, over the [pitch angle](https://en.wikipedia.org/wiki/Blade_pitch). Pitch angle/feathering angle is a 2 part measure — the local "pitch" (Z) & "roll" (X) of the blade.

## P4 & beyond

## A brief note on universal points & vectors.

It seems like we have a universal latent space of color through the web. The [named CSS colors](https://en.wikipedia.org/wiki/Web_colors) are simply labels within the HEX possible space.

- HEXA (HEX for RGB with an A bit at the end) is for computers
- [CIELAB](https://en.wikipedia.org/wiki/CIELAB_color_space) is a perceptive color space as it establishes [human-centered metrics](https://en.wikipedia.org/wiki/Color_difference#Tolerance):

- `L` for perceptive color
- `a` & `b` to move through the human color space of RGBY.