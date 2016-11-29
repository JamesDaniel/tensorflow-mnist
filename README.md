# A working repo for tensorflow training on mnist

## System Requirements

- Ubuntu 14
- 64bit system
- >500mb memory
- Python 2.7.6

## Steps to take

- sudo apt-get install python-pip python-dev
- sudo pip install virtualenv
- virtualenv ./ --no-site-packages
- source bin/activate
- pip install -r requirements.txt
- pip freeze
- mv test.py lib/python2.7/site-packages
- cd lib/python2.7/site-packages
- python test.py

## References

- https://www.tensorflow.org/versions/r0.12/tutorials/mnist/beginners/index.html
