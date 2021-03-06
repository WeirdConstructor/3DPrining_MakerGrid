# MakerGrid - A 3D Printed grid system for makers

This system allows you to temporarily setup electronics or other
devices on an extensible modular base platform:

![MakerGrid Demonstration Prototype](res/makergrid_demo_2.jpg)

The base is this 12x12cm big and 1cm high base platform:

![MakerGrid 12x12cm base platform with 2x2cm clip grid](res/maker_grid_2cm.png)

The primary base platform is 12x12cm big, 1cm high and has a 2x2cm grid for
clipping in all sorts of stuff, such as:

- Bread boards
- Electronics modules such as:
  - Arduino Uno / Nano
  - Raspberry Pi 4
  - Raspberry Pi Pico

The system is extensible as with the generic clip design you can make
your own models to clip into the board. A clip looks like this:

![MakerGrid Clip](res/clip_10mm.png)

The clips hold well in the holes, you will need either strong fingers or
pliers to pull them out again. The clip arms will be printed with 3 0.4mm thick
walls, which provide enough flexibility while also holding tight.
The clips also provide a rotational stability.

The advantage of this system that connects holes is also,
that if you damage a clip, you can reprint them quickly.

There is a whole palette for holdes/clip holders to choose from in the `clip.blend`
file:

![MakerGrid Clip Palette](res/clip_10mm_models.png)

## Prior Art

I was inspired by:

- 3D Printing Professor's PrintABlok
  - While I like this approach and it's design is superior to mine, I wanted
    something a bit more compact and less bulky.
  - https://www.youtube.com/watch?v=BU7ZYPHWDo4
  - https://www.3dpprofessor.com/product/printablok-base-set-free/
  - https://www.thingiverse.com/thing:4965875
- Pin Connectors V2
  - I like the simplicity of this design, but these round connectors
    would make the MakerGrid too wobbly if not connected by at least two
    pins. My grid clips are rectangular and already provide some stability
    if you just plug in a single one.
  - https://www.thingiverse.com/thing:10541

## Maker Grid Types:

- Regular Full:
![MakerGrid 12x12cm base platform with 2x2cm clip grid](res/maker_grid_2cm.png)
- Type B:
![MakerGrid 12x12cm base platform type B](res/maker_grid_2cm_type_b.png)
- Type C:
![MakerGrid 12x12cm base platform type C](res/maker_grid_2cm_type_c.png)
- Type D:
![MakerGrid 12x12cm base platform type D](res/maker_grid_2cm_type_d.png)

## Utilities

- Build Cubes in sizes 1x1, 3x1, 7x1, 11x1, 15x1 offer a way to extend
  the maker grid into 3 dimensions.
    - Also with a slim variant that has the "\_s" as postfix.
    - And a base extension variant, that can be plugged to the side
      of the MakerGrid bases with an "\_x" postfix.

![MakerGrid Build Cubes](res/build_cubes.png)

- Raspberry Pi 2/3/4 B Holder

![Raspberry Pi Holder](res/raspberry_pi_plate_holder.png)

- Raspberry Pico Holder

![Raspberry Pi Pico Holder](res/raspberry_pico_plate_holder.png)

- **Make sure to checkout the subdirectory** `blender` **for more!**

## Recommended Printer Settings

Basically you can print it in any way you like, but I recommend
following settings for printing:

- 0.4mm nozzle
- 0.3mm layer height
- For the clips themself I recommend a wall thickness of 1.6mm: ![Sliced Maker Grid Clip](res/sliced_clip.png)
For the other parts even 0.8mm works fine.

The rest you can vary to your likings. I printed it in PLA. Not tried
it in PETG or ABS/ASA yet, but should be even better for the clips (due to
better flexibility).

## License

3D MakerGrid by Weird Constructor is licensed under the
Creative Commons - Attribution - Share Alike license.
