# handwired/2_key_macropad

![Image](https://media.printables.com/media/prints/1b548c00-1e38-435e-ac8e-3ecc0696e820/images/10080525_1d3af5ef-5f36-4597-b425-f2d3c54f2664_c3569934-6a74-4e4e-92ad-8e2d67c67136/thumbs/inside/1920x1440/jpg/2_key_macropad1.webp)

## 3D files

[Printables](https://www.printables.com/model/1336078-2-key-macropad-with-a-knob)

Make example for this keyboard (after setting up your build environment):

    make 2_key_macropad:default

Flashing example for this keyboard:

    make 2_key_macropad:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
