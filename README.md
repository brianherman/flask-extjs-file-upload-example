This is a web based compiler for llvm.
======================================

Installation
=============================
Install emscripten and llvm.
Welcome Back::

    pythonbrew use Python-2.7.1
    source $HOME/.venvburrito/startup.sh
    workon flask_file_upload

Initial::

    pythonbrew use Python-2.7.1
    curl -s https://raw.github.com/brainsik/virtualenv-burrito/master/virtualenv-burrito.sh | bash
    source $HOME/.venvburrito/startup.sh
    # be sure to add the above to your ~/.bashrc
    mkvirtualenv --no-site-packages --distribute flask_file_upload
    workon flask_file_upload

    cd static/js
    # download and extract extjs here
    wget http://extjs.cachefly.net/ext-4.0.2a-gpl.zip
    unzip
    ln -s extjs ext-4.0.2a-gpl/
    cd ../../

    python app.py

See https://github.com/brainsik/virtualenv-burrito#readme

Now to the app itself

http://flask.pocoo.org/docs/patterns/fileuploads/
The MIT License (MIT)

Copyright (c) 2013 Brian James Herman

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


.. vim: set fileencoding=utf-8 filetype=rst :

