
.. install and launch DORIS



**DORIS** can be downloaded from the `GiHub repository <https://github.com/olivierfriard/doris/releases>`_

All versions (Windows and Mac) are *portable*, they do not need to be installed on your system.

All previous versions of **DORIS** are available in the GitHub repository.



GNU/Linux
------------------------------------------------------------------------------------------------------------------------

DORIS run with Python < 3.8

* Create a virtual environment (to isolate DORIS from your system):


.. code-block:: bash

   python3 -m venv doris_venv


* Activate the virtual environment

.. code-block:: bash

   source doris_venv/bin/activate


The prompt should now be prefixed by **doris_venv**


* Install DORIS


.. code-block:: bash

   pip install doris-tracker


* Launch DORIS


.. code-block:: bash

   python3 -m doris


Microsoft-Windows
------------------------------------------------------------------------------------------------------------------------

Download the **doris-x.y.z-win64-portable.zip** file, unzip it and launch **start_doris.bat**.

Mac OS
------------------------------------------------------------------------------------------------------------------------

Download the **doris-x.y.z.dmg** image file, mount it and launch the **DORIS** program.




The easy way: run DORIS from packages
------------------------------------------------------------------------------------------------------------------------

The executable versions of DORIS can be downloaded from the **Releases section** of 
the `GitHub repository <https://github.com/olivierfriard/DORIS/releases>`_

Extract the archive and launch the **doris** executable file




The expert way: run DORIS from sources (for Mac and Linux)
------------------------------------------------------------------------------------------------------------------------


To run DORIS from source you must have a running version of Python => 3.6

Create a virtual environment and activate it
.............................................


    python3 -m venv doris_venv

    source doris_venv/bin/activate

Install the dependencies
.............................................


    pip3 install numpy matplotlib opencv-python-headless pandas pyqt5 scikit-learn scipy sklearn


Download the DORIS source
.............................................


if git is installed and is present in the path

    git clone https://github.com/olivierfriard/DORIS.git

    cd DORIS

if git is not installed

    wget https://github.com/olivierfriard/DORIS/archive/master.zip
    unzip master.zip

    cd DORIS-master/src


Launch DORIS
.............................................


    python3 doris.py





