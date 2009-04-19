IntegrityMenu
==============================================================================

IntegrityMenu is a Mac OS X dashboard widget for showing project status from
an instance of an Integrity (http://integrityapp.com) continuous integration
server. 

IntegrityMenu only requires two settings:
  1. The URL of the integrity server to monitor (by default this is set to the
     URL of Integrity itself).
  2. The amount of time that the server will wait to update the project
     status (5 minutes by default).

To have this widget appear on your desktop once you have installed it on the
  dashboard, activate Dashboard development mode (thanks to
  http://www.macosxhints.com/article.php?story=20050422172929402)

1. Open the Terminal and enter:
     defaults write com.apple.dashboard devmode YES
2. Logout and log back in again.
3. Activate Dashboard by pressing F12 (or whatever key you've assigned to
     Dashboard).
4. Begin dragging the widget.
5. Press F12 again, before letting up on the mouse button.
     Drop the widget wherever you want it.

License
==============================================================================
The MIT License

Copyright (c) 2009 Bill Siggelkow

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
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
==============================================================================

