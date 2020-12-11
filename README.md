dupePad
========
As many of you may know, the Frogpad keyboard is dying and the hardware may not be manufactured again. 
In effort to preserve the frogpad layout that many people have devoted much time into learning, this project remaps the frogpad layout on a standard qwerty keyboard for Windows and Mac. 
The frogpad remap uses autohotkey for Microsoft Windows (and can be compiled to a portable .exe file) and Karabiner-Elements for Mac.

Instructions:
========

# WINDOWS:
This script uses autohotkey(http://www.autohotkey.com/download/) and can convientely be compiled to a 80kb exe file!
This is very useful because the small file can be stored in email, on a portable usb drive, or on a network drive.
To do this, after autohotkey is installed, right click and "compile to .exe." I would link to this directly, but because of security concers, I encourage you to do this yourself.

# MAC:

-   Download and install [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
-   Download remap (use entire line):

   -   Right: <karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/clarkm/dupepad/master/karabiner-elements/frogpad-right.json>

   -   Left: <karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/clarkm/dupepad/master/karabiner-elements/frogpad-left.json>

-   **NOTE**: _Only the letters are remapped - all other keys on standard qwerty keyboard remain the same_

-   Capital letters work by standard shift and caps-lock keys

-   Go to http://frogpad.com/ for:

    -   Windows "qwerty-frog"
    -   Mac "qwerty-frog" for earlier macOS versions (10.11 and below)
    -   Training game for practice!

## System requirements

-   MacOS 10.12 (Sierra) - MacOS 11 (Big Sur) and later

## To install:

1. Download and install the app Karabiner-Elements: https://pqrs.org/osx/karabiner/

2. Download and import keymap by going to this link and opening it with Karabiner-Elements:

   Right: <karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/clarkm/dupepad/master/karabiner-elements/frogpad-right.json>

   Left: <karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/clarkm/dupepad/master/karabiner-elements/frogpad-left.json>

3. In Karabiner-Elements, go to "Preferences" > "Profiles" tab > "Add profile",
   name the profile, "Frogpad" for example, and click "Select".

4. "Complex Modifications" tab > "Add rule", and enable "Frogpad".

## To update:

1. In Karabiner-Elements > "Preferences" > "Profiles" tab, "Select" the Frogpad
   profile.

2. "Complex Modifications" tab > "Rules", "Remove" the Frogpad rule.

3. Click "Add rule" and delete/trash "Frogpad".

4. In a browser, go to the same link and import:

   Right: <karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/clarkm/dupepad/master/karabiner-elements/frogpad-right.json>

   Left: <karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/clarkm/dupepad/master/karabiner-elements/frogpad-left.json>

5. For "Frogpad", click "Enable".

6. Check one more time in the "Profiles" tab that it was added to your Frogpad
   profile.

## Keymap (Right Hand)
-   For "Primary" keys, simply type as normal with right hand.
-   To activate "Secondary" keys, hold down (spacebar) while typing.
-   _Special note that the < and > keys that become lost in this layout are now remapped to the left-shift+Z and left-shift+X keys respectively._

| Default        | Primary        | Secondary                    |
| -----------    | -------------- | ---------------------------- |
| (spacebar)     | (spacebar)     | N/A                          |
|      o         | p              |	j                            |
|      i	        | w              |	m                            |
|      u	        | r              |	b                            |
|      y	        | a              |	' (quote)                    |
|      t	        | f              |	(tab)                        |
|      l	        | d              |	v                            |
|      k	        | t              |	c                            |
|      j	        | h              |	l                            |
|      h	        | e              |	z                            |
|      g	        | o              |	q                            |
|      .   	     | y              |	x                            |
|      ,         | s              |	g                            |
|      m	        | n              |	k                            |
|      n	        | i              |(backspace or delete backward)|
|      b	        | u              |	(delete forward)             |
| (right-cmd)    | N/A            |	, (comma)                    |
| (right-alt)    | (return/enter) |    . (period)                |
| (left-shift)+z |	<            |    N/A                       |
| (left-shift)+x |	>            |	   N/A                       |


## Keymap (Left Hand)
-   For "Primary" keys, simply type as normal with left hand.
-   To activate "Secondary" keys, hold down (spacebar) while typing.

| Default     | Primary        | Secondary                       |
| ----------- | -------------- | ------------------------------- |
| (spacebar)  | (spacebar)     | N/A                             |
| q           | p              | j                               |
| w           | w              | m                               |
| e           | r              | b                               |
| r           | a              | ' (quote)                       |
| t           | f              | (tab)                           |
| a           | d              | v                               |
| s           | t              | c                               |
| d           | h              | l                               |
| f           | e              | z                               |
| g           | o              | q                               |
| z           | y              | x                               |
| x           | s              | g                               |
| c           | n              | k                               |
| v           | i              | (backspace or delete backwards) |
| b           | u              | (delete forward)                |
| (left-alt)  | N/A            | , (comma)                       |
| (left-ctrl) | (return/enter) | . (period)                      |

## Hardware Example

![alt text](https://lh3.googleusercontent.com/proxy/VASljlh3k8z7Q8JdfYLXXj0OFow9_jOyPOaEIhBXYb-EkefdBsp3ZfS49JGp8ok7IrQkHaTIHwqyp5ZIudOJ0XpCeYksdw_CsMXCfkL95yE "Frogpad keyboard (Right hand)")

![alt text](https://cdn.shopify.com/s/files/1/2603/0286/products/FPBKUSB30Right_512x.jpg?v=1516043628 "Frogpad keyboard (left hand)")

## Other Resources

-   https://www.youtube.com/watch?v=TmzYovAMHE4
-   https://www.youtube.com/watch?v=HLXdF3I7ItA
-   https://www.youtube.com/watch?v=471Dcyauf44
-   http://www.frogpad.com/FrogPad/Support.html
-   http://www.frogpad.com/FPInfo-SoftFrog.html

# MAC OS X 10.11 El Capitan and earlier:
This uses the helper utility, "KeyRemap4MacBook" (https://karabiner-elements.pqrs.org/) and is done with custom remaps to the private.xml file.
To do this you must go in to System Preferences > KeyRemap4MacBook > Misc & Uninstall > open private.xml. Once there, use the xml file from this repo for the rest.
