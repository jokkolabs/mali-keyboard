Mali Keyboard Layout
=====================

A Keyboard Layout containing additional characters for easy typing of Bamanankan/Songhay text.

It is available in tree variants: French, English (US) and English (International)


xkeyboard-config
----------------

The layout has been integrated upstream: http://cgit.freedesktop.org/xkeyboard-config/tree/symbols/ml

On Ubuntu at least, there are recurrent conflicts between this layout and the Malayalam one. See [Launchpad #575660](https://bugs.launchpad.net/ubuntu/+source/xkeyboard-config/+bug/575660) for more details.

A quick fix consist in renaming the `ml` symbol to `mali` and changing it's reference in _evdev.xml_.

