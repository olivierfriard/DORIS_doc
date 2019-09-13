.. install and launch DORIS


The easy way: run DORIS from binaries
--------------------------------------------------------------------------------------------------------------------------------------------

The executable/binary versions of DORIS can be downloaded from the **Releases section** of the `GitHub repository <https://github.com/olivierfriard/DORIS/releases>`_

Extract the archive and launch the **doris** executable file




The expert way: run DORIS from sources (for Mac and Linux)
--------------------------------------------------------------------------------------------------------------------------------------------


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





