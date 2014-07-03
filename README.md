
# The pain machine


This is the control software for the pain machine, intended to run on the raspberry pi.



To install:

    sudo pip install virtualenvwrapper
    mkvirtualenv pain

    git clone https://github.com/puterleat/painmachine.git
    cd painmachine
    pip install -r requirements.txt


To run:

    python painserver.py


Then open [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in a reasonable browser (not tested in IE, and certainly won't work in an old IE).

