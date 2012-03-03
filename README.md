# nodeGame

Javascript framework (node.js + socket.io) for online multiplayer games in the browser.

---

## Setup (Dev-Env for Unix Systems)

      # Install the Node.js Server
      $ git clone git://github.com/joyent/node.git
      $ cd node/
      $ git checkout v0.6.11
      $ ./configure
      $ sudo make
      $ sudo make install
  
      # Clone nodeGame
      $ cd /into/the/place/where/you/put/project/folders
      $ git clone git://github.com/shakty/nodeGame.git
      $ cd nodeGame/
  
      # Install Dependencies
      $ cd server/
      $ npm install (be aware of http://goo.gl/T8m9d)
  
      # Make a clean build of the nodeGame scripts for the client
      $ node makefile.js
  
      # Start the management server
      $ node server.js
  
      # Open 2 different browser instances with the pr-example
      $ open FILE_PATH_TO_REPO/examples/pr/index.htm
  
      # (optional) Monitor the game via the browser
      $ open FILE_PATH_TO_REPO/examples/pr/monitorgame.html
  
      # Start the game
      $ cd client/nodeclient
      $ node pr.js
  
      # Game runs through (might not be too obvious)

## Example

See doc folder for now.

## License

Copyright (C) 2012 Stefano Balietti

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
