tessel-relay
============


![tessel-relay](http://reelyactive.github.io/images/tesselHub-connected.jpg)


Prerequisites
-------------

You will require a [Tessel 2](https://tessel.io/) and our [minimal starter kit](http://shop.reelyactive.com/products/starterkit-min).  See our [Make a Tessel Hub](http://reelyactive.github.io/make-a-tessel-hub.html) tutorial for details.  Complete the [Tessel 2 Installation](http://tessel.github.io/t2-start/) to ensure that the Tessel 2 is connected and updated, and the t2-cli command-line tools are installed.  Connect the minimal starter kit via the Tessel 2's USB port.


Installation
------------

Clone the repo.

    npm install


Running in RAM
--------------

To run the program in RAM, from the root of the repository run:

    t2 run index.js

On some systems you may need to prefix this with _sudo_.


Writing to Flash
----------------

To write the program to Flash so that it runs automatically whenever the Tessel 2 powers up, from the root of the repository run:

    t2 push index.js

On some systems you may need to prefix this with _sudo_.


How do I know it's working?
---------------------------

The program is configured by default to send the data to our [Pareto platform](https://pareto.reelyactive.com).  A three-month trial is included with the [starter kit](http://getpareto.com/starter-kit/)  Log in to view the real-time data from the dashboard.

Prefer to stream the data to a different server?  Simply update the _hostname_ in the index.js file.


License
-------

MIT License

Copyright (c) 2016 reelyActive

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN 
THE SOFTWARE.

