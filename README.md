**PowerAudio fork of tap-lv2**

This fork of tap-lv2 has the following changes:

* SSE flags are used only on x86, fixing compilation for other architectures.

---

tap-lv2
=======

LV2 port for the TAP (Tom's Audio Processing) plugins

Author: Tom Szilagyi <tszilagyi@users.sourceforge.net>

Webpage: http://tap-plugins.sf.net

Check the original README file for more information


compile and install
===================

make

make INSTALL_PATH=~/.lv2/ install

(or any other dir, defaults to /usr/local/lib/lv2/)