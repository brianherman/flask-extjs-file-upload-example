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

.. vim: set fileencoding=utf-8 filetype=rst :
