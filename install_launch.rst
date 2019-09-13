.. install and launch DORIS


Run DORIS from binaries
--------------------------------------------------------------------------------------------------------------------------------------------

The executable/binary versions of DORIS can be downloaded from the **Releases section** of the `GitHub repository <https://github.com/olivierfriard/DORIS/releases>`_

Extract the archive and launch the **doris** executable file




Run DORIS from sources
--------------------------------------------------------------------------------------------------------------------------------------------


To run DORIS from source you must have a running version of Python => 3.6

Create a virtual environment
.............................................


    python3 -m venv doris_venv

    source doris_venv/bin/activate

    pip3 install numpy matplotlib opencv-python-headless pandas pyqt5 scikit-learn scipy sklearn

if git is installed and in the path

    git clone https://github.com/olivierfriard/DORIS.git

if git is not installed

    wget https://github.com/olivierfriard/DORIS/archive/master.zip
    unzip master.zip

    cd DORIS/src

    python3 doris.py





