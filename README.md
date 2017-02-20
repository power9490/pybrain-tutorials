# pybrain-tutorials

## motivation
The documentation is build up in the following parts: first, there is the quickstart tutorial which aims at getting you started with PyBrain as quickly as possible. This is the right place for you if you just want get a feel for the library or if you never used PyBrain before.
Although the quickstart uses supervised learning with neural networks as an example, this does not mean that that’s it. PyBrain is not only about supervised learning and neural networks.
While the quickstart should be read sequentially, the tutorial chapters can mostly be read independently of each other.
In case this does not suffice, we also have an API reference, the Module Index. Most of the packages and modules of PyBrain are auto-documented there.
If you want to develop for PyBrain and contribute, check out our guidelines in our wiki: http://wiki.github.com/pybrain/pybrain/guidelines.
If at any point the documentation does not suffice, you can always get help at the pybrain Google Group at http://groups.google.com/group/pybrain.

## context

## installation
### Get it

Make sure you have the dependencies.

Option 1: If you have setuptools/easy_install, you can get the latest stable release from the cheeseshop directly, and set up automatically:

	$ easy_install structure pybrain 

Option 2: Download it from here. Unpack it.
Option 3: Get the bleeding edge from the git repository:

	$ git clone https://github.com/pybrain/pybrain.git 

### Set it up

If you have setuptools, run (you may need to do this as superuser on Unix systems):

	$ python setup.py install 

If the above fails, you can also try installing with pip via:

	$ cd pybrain 
	$ sudo pip install . 

Alternatively run pip install . --user to install it for the current user only.
Otherwise: Update the PYTHONPATH environment variable to include the location of pybrain. 

	$ export PYTHONPATH=$PYTHONPATH:`pwd` 

### Verify

	$ python
	Python 2.5.2 (r252:60911, Sep 17 2008, 11:21:23)
	Type "help", "copyright", "credits" or "license" for more information.
	>>> import pybrain
	>>>

Or if you want to be more thorough:

	$ cd pybrain/tests
	$ python runtests.py
	INFO Tests found: […]
	...............................
	----------------------------------------------------------------------
	Ran 31 tests in 8.749s
	OK
  
