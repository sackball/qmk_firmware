# ð GOAT51

![takashicompany/GOAT51](https://i.imgur.com/7xD9a4zh.jpg)

GOAT51ã¯51ã­ã¼ã®ã­ã¼ãã¼ãã§ãã
ç¹å¾´çãªæ¾å°ç¶ã®ã­ã¼ã¬ã¤ã¢ã¦ãã¯æãèªç¶ã«ç½®ããã¨ãã§ããå¹ççãªå¥åãå¯è½ã§ãã
MXäºæã®ã­ã¼ã¹ã¤ããã¨Choc v1ã­ã¼ã¹ã¤ããã®åãä»ãã«å¯¾å¿ãã¦ããã¾ãã
ã¾ãPCBã«ã­ã¼ã¹ã¤ããã½ã±ãããåãä»ãããã¨ãå¯è½ã§ãå®¹æã«ã­ã¼ã¹ã¤ããã®äº¤æãã§ãã¾ãã
ã­ã¼ãã¼ãã®ä¸­å¤®ã«ã¯ãæ°ã«å¥ãã®ã­ã¼ã­ã£ãããåãä»ããå°ç¨ã¹ãã¼ã¹ããããã¢ã«ãã¶ã³ã­ã¼ã­ã£ããããæ°ã«å¥ãã®ã­ã¼ã­ã£ãããé£¾ããã¨ãã§ãã¾ãã
å®ã¯ããã«ã¯ã­ã¼ã¿ãªã¼ã¨ã³ã³ã¼ããç½®ããã¨ãã§ãã¡ããã¾ãã

---
GOAT51 is a 51-key keyboard.
The distinctive radial key layout allows the fingers to be placed naturally for efficient typing.
It supports the installation of MX compatible key switches and Choc v1 key switches.
A key switch socket can also be installed on the PCB for easy keyswitch replacement.
There is a dedicated space in the center of the keyboard for mounting your favorite keycaps, allowing you to display Artisan keycaps or your favorite keycaps.
In fact, you can even place a rotary encoder there.

* Keyboard Maintainer: [takashicompany](https://github.com/takashicompany)
* Hardware Supported: GOAT51 PCB, Pro Micro
* Hardware Availability: https://github.com/takashicompany/goat51

Make example for this keyboard (after setting up your build environment):

    make takashicompany/goat51:default

Flashing example for this keyboard:

    make takashicompany/goat51:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
