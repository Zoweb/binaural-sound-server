## Binaural Sound Server
#### A Spigot and NodeJS Binaural Sound server.

Binaural Sound Server is a Spigot plugin that allows servers to give players a [binaural](https://en.wikipedia.org/wiki/Binaural_recording "Binaural Recording") experience playing on a Spigot server.
Players must be wearing headphones for this plugin to have any effect.

### How do I use the Binaural Sound Server?
1. Download the repository as a ZIP (click `Clone or download` and then `Download ZIP`)
2. Extract the `out/artifacts/binaural_sound_server_1.0/binaural-sound-server-1.0.jar` to your Spigot server's `plugins` folder.
3. Start up your server to generate all the required files.
4. Extract the `out/server` folder to your NodeJS-enabled server
5. Create a page that opens a popup or iframe of the above server's `sound-server` folder (for example, `binaural-sound-server.heroku.com/`**`sound-server`**`#player-name`) - make sure to put in the player's name there.
6. Run the NodeJS server using `node "path/to/server"`. If you are running this on your own computer, make sure you have port-forwarded the port specified in the `out/server/port.txt` file (default
71963).

This project uses Ircam-RnD's binauralFIR project - https://github.com/Ircam-RnD/binauralFIR.

#### LICENSE

    MIT License

    Copyright (c) 2016 zoweb

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
