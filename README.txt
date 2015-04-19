Blokel
========

Blokel is a game inspired by Cube World. Its goal is to make a game that has RPG elements like Cube World, but have that voxel experience that Minecraft has. As well as to have tons of exploration features provided in Terraria and Minecraft. Nonetheless, we accept hate comments calling it a Minecraft clone, a 3D terraria clone, and a Cube World clone, because that is exactly what it is.
Blokel is not released, but you can compile the current source to see the progress so far, with instructions below.

Copyright (c) 2015 Preston (Marth) Cammarata
and contributors from all over the globe (edits from "blokel" or "devmarth" are the same person. which is the lead developer of blokel, as said above)

Source based on Minetest <minetest.net>

Join us on IRC at #blokel (or #blokel-dev for developers) @freenode.net

In case you downloaded the source code:
---------------------------------------
If you downloaded the Blokel Engine source code in which this file is
contained, you probably want to download the blokel_game project too:
  https://github.com/blokel/blokel_game/
See the README.txt in it. (this adds features to the game, rather than it be a minimal test)

Further documentation
----------------------
Because it's based on Minetest, documentation is hosted there temporarily, but for now, that'll do.
- Website: http://minetest.net/
- Wiki: http://wiki.minetest.net/
- Developer wiki: http://dev.minetest.net/
- Forum: http://forum.minetest.net/
- Github: https://github.com/minetest/minetest/
- doc/ directory of source distribution

This game is not finished
--------------------------
- Don't expect it to work as well as a finished game will.
- Please report any bugs. When doing that, debug.txt is useful.

Default Controls
-----------------
- WASD: move
- Space: jump/climb
- E: Run
- Shift: sneak/go down
- Q: drop itemstack (+ SHIFT for single item)
- I: inventory
- Mouse: turn/look
- Mouse left: dig/punch
- Mouse right: place/use
- Mouse wheel: select item
- T: chat
- 1-8: select item

- Esc: pause menu (pauses only singleplayer game)
- R: Enable/Disable full range view
- +: Increase view range
- -: Decrease view range
- K: Enable/Disable fly (needs fly privilege)
- J: Enable/Disable fast (needs fast privilege)
- H: Enable/Disable noclip (needs noclip privilege)

- F1:  Hide/Show HUD
- F2:  Hide/Show Chat
- F3:  Disable/Enable Fog
- F4:  Disable/Enable Camera update (Mapblocks are not updated anymore when disabled)
- F5:  Toogle through debug info screens
- F6:  Toogle through output data
- F7:  Toggle through camera modes
- F10: Show/Hide console
- F12: Take screenshot


Compiling
--------------------------------------
Currently, Blokel is only supported on Linux based operating systems. All compile instructions are the same as Minetest. So if there are no instructions for your current distro, google it for Minetest.

Ubuntu:
- Create a .sh file with the script from http://pastebin.com/j6tmWKNg
- Goto terminal, and goto the directory with script inside of it, and chmod the file so you can run it. (chmod +x)
- Type ./compilescript.sh (it can be named anything, but compilescript.sh is an example)

Fedora:
- Create a .sh file with the script from http://pastebin.com/QepTnwGt
- Goto terminal, and goto the directory with the script inside of it, and chmod the file so you can run it. (chmod +x)
- Type ./compilescript.sh (it can be named anything, but compilescript.sh is an example)
- If there are errors, install the dependencies found in the script manually and then compile it.



Note:
- This game is not even closed to being finished, so the only way you can play is by compiling the source yourself. 
- Do not expect this to be perfect. It will be buggy, sometimes slow, and even not work at all.


License of Minetest textures and sounds
---------------------------------------

This applies to textures and sounds contained in the main Minetest
distribution.

Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)
http://creativecommons.org/licenses/by-sa/3.0/

Authors of media files
-----------------------
Everything not listed in here:
Copyright (C) 2010-2012 celeron55, Perttu Ahola <celeron55@gmail.com>

BlockMen:
  textures/base/pack/menuheader.png

erlehmann:
  misc/minetest-icon-24x24.png
  misc/minetest-icon.ico
  misc/minetest-icon.svg
  textures/base/pack/logo.png

License of Minetest source code
-------------------------------

Minetest
Copyright (C) 2010-2013 celeron55, Perttu Ahola <celeron55@gmail.com>

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation; either version 2.1 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

Irrlicht
---------------

This program uses the Irrlicht Engine. http://irrlicht.sourceforge.net/

 The Irrlicht Engine License

Copyright © 2002-2005 Nikolaus Gebhardt

This software is provided 'as-is', without any express or implied
warranty. In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute
it freely, subject to the following restrictions:

   1. The origin of this software must not be misrepresented; you
      must not claim that you wrote the original software. If you use
	  this software in a product, an acknowledgment in the product
	  documentation would be appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must
      not be misrepresented as being the original software.
   3. This notice may not be removed or altered from any source
      distribution.


JThread
---------------

This program uses the JThread library. License for JThread follows:

Copyright (c) 2000-2006  Jori Liesenborgs (jori.liesenborgs@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.

Lua
---------------

Lua is licensed under the terms of the MIT license reproduced below.
This means that Lua is free software and can be used for both academic
and commercial purposes at absolutely no cost.

For details and rationale, see http://www.lua.org/license.html .

Copyright (C) 1994-2008 Lua.org, PUC-Rio.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Fonts
---------------

DejaVu Sans Mono:

  Fonts are (c) Bitstream (see below). DejaVu changes are in public domain.
  Glyphs imported from Arev fonts are (c) Tavmjong Bah (see below)

Bitstream Vera Fonts Copyright:

  Copyright (c) 2003 by Bitstream, Inc. All Rights Reserved. Bitstream Vera is
  a trademark of Bitstream, Inc.

Arev Fonts Copyright:

  Copyright (c) 2006 by Tavmjong Bah. All Rights Reserved.

Liberation Fonts Copyright:

  Copyright (c) 2007 Red Hat, Inc. All rights reserved. LIBERATION is a trademark of Red Hat, Inc.

DroidSansFallback:

  Copyright (C) 2008 The Android Open Source Project

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.

