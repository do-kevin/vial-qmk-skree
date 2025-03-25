0. `qmk setup` and `brew install --cask gcc-arm-embedded`

-   ref: https://github.com/ARMmbed/homebrew-formulae

1. Be in keyboards

2. Run `qmk compile -kb do_kevin/smoll/trackball/dualtb6x7_6_5 -km vial`

To reset:

`qmk compile -kb skree/smoll/trackball/dualtb6x7_6_5 -km vial`

and go into bootloader mode with rp2040 or whatever it is called. HOld reset button before plugging into usb. Then drag uf2 file into the USB controller
