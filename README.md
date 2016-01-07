WASD keycaps for Varmilo VB87M keyboard
=======================================

The Varmilo VB87M is one of the few mechanical keyboards that is also 
wireless, and also nominally Mac compatible. Availability is spotty, but 
it can periodically be
[purchased through Massdrop](https://www.massdrop.com/buy/varmilo-vb87m-bluetooth)
for around USD $130.

The model I ordered is black, with Gateron Brown switches and light 
grey, top-printed dye sub keycaps:
![Varmilo VB87M](raw/master/images/varmilo_vb87m.jpg)

The keyboard look and feel has some problems:

* The default color options are highly conspicuous (grey, white, or green).
* All of the mechanical switch options are quite loud.
* The classic PC layout has a Windows key, <kbd>Alt</kbd>, and so on, non-ideal for Mac usage.
* The raised bumps on <kbd>F</kbd> and <kbd>J</kbd> are a bit too small.

An [87 key Cherry MX keycap set](http://www.wasdkeyboards.com/index.php/products/keycap-set/87-key-cherry-mx-keycap-set.html)
from [WASD Keyboards](http://www.wasdkeyboards.com/)
can address all of these problems: keys are available in black or dark 
grey, with o-rings to slightly dampen key click, and in a Mac layout. 
The raised bumps on <kbd>F</kbd> and <kbd>J</kbd> are more noticeable
than those on the keys that ship with the Varmilo VB87M.

WASD Keyboards offers a
[Mac hotkey shortcuts keycap set](http://www.wasdkeyboards.com/index.php/products/keycap-mod-packs/mac-hotkey-shortcuts-cherry-mx-keycap-set.html)
for normal Mac keyboards; however, the media keys on the Varmilo VB87M 
are slightly astandard:

![Varmilo VB87M media keys](raw/master/images/varmilo_media_keys.jpg)

* <kdb>Fn</kbd>+<kbd>F7</kbd> = Mute
* <kdb>Fn</kbd>+<kbd>F8</kbd> = Volume Up
* <kdb>Fn</kbd>+<kbd>F9</kbd> = Volume Down
* <kdb>Fn</kbd>+<kbd>F10</kbd> = Play/Pause
* <kdb>Fn</kbd>+<kbd>F11</kbd> = Rewind/Previous Track
* <kdb>Fn</kbd>+<kbd>F12</kbd> = Fast Forward/Next Track
* <kdb>Print Screen</kbd> = <kbd>F13</kbd>
* <kdb>Scroll Lock</kbd> = Brightness Down (does _not_ register as <kbd>F14</kbd>)
* <kdb>Pause</kbd> = Brightness Up (does _not_ register as <kbd>F15</kbd>)

Finally, there are a few keyboard-specific shortcuts, most usefully:

* <kdb>Fn</kbd>+<kbd>Insert</kbd> = Toggle keyboard power
* <kdb>Fn</kbd>+<kbd>→</kbd> = Enter Bluetooth pairing mode

Install
-------

Install Inkscape, which requires XQuartz:

* https://inkscape.org/en/
* http://www.xquartz.org/

Install VAG Rounded Light font:

* http://www.fontpalace.com/font-details/VAGRounded-Light/

Download Bluetooth icon vector graphic:

* https://en.wikipedia.org/wiki/File:Bluetooth_white_tray_icon.svg

Download WASD Keyboard layout templates:

* http://support.wasdkeyboards.com/customer/portal/articles/1380026-layout-template-files
* http://support.wasdkeyboards.com/customer/portal/kb_article_attachments/67914/original.svg?1445632730

On `Mac` layer (using font `VAG Rounded Light` 9pt):

* Replace function keys with uppercase variants
* Remove <kbd>F14</kbd> and <kbd>F15</kbd>
* Change <kbd>caps lock</kbd> to <kbd>control</kbd>

On `Mods - Media Keys` layer:

* Add mute icon to <kbd>F7</kbd>
* Add play/pause icon to <kbd>F10</kbd>
* Add fast forward/next track icon to <kbd>F11</kbd>
* Add rewind/previous track icon to <kbd>F12</kbd>

On `Stock Artwork` layer:
- Add volume down icon to <kbd>F8</kbd>
- Add volume up icon to <kbd>F9</kbd>
- Add brightness down icon to former <kbd>F14</kbd>
- Add brightness up icon to former <kbd>F15</kbd>
- Add power icon to <kbd>insert</kbd>

Add new `Bluetooth Icon` layer:
- Add Bluetooth icon (foreground only, stroked to black) to <kbd>→</kbd>

Icons are scaled to match mute icon height (7.998px) as reference.
