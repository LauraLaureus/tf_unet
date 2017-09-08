============
Installation
============

The project is hosted on GitHub. Get a copy by running::

	$ git clone https://github.com/jakeret/tf_unet.git
	
	
Install the package like this::

	$ cd tf_unet
	$ pip install -r requirements.txt
	$ python setup.py install --user
	
Alternatively, if you want to develop new features::

	$ cd tf_unet
	$ python setup.py develop --user

Make sure `TensorFlow` is installed on your system. Installation instruction can be found `here <https://www.tensorflow.org/get_started/os_setup.html>`_


*Visual Studio*

Download the unet repo by Git client or the .zip folder. 

Take the _unet_ folder and move it to the _sites-package_ in the path <yourPythonInstalation>/Lib/sites-packages

Open Visual Studio and open Python enviroments. Select the Python enviroment related to the folder we have just move unet.
Select in the combobox IntelliSense and press Update Database. 
