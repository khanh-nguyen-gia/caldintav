Overview
=========================

Caldintav is a program developed by GCM in Python to calculate the
dynamic responses of the bridges under the railway traffic loadings. 

The program offers:

    1. Can be used for analyzing both types of bridges:  simply-supported and continuous bridges
    2. Determine the time history of displacement and acceleration at the mid-span of the  bridge
    3. Determine the envelope of the maximum dynamic responses for a range of train velocities
    4. Can be used to perform a parametric calculation for various bridges and trains.



Getting the latest code
=========================

To get the latest code using git, simply type::

    git clone https://github.com/khanh-nguyen-gia/caldintav.git

If you don't have git installed, you can download a tar.gz file
of the latest code: https://github.com/khanh-nguyen-gia/caldintav/tree/main/dist

Requirements
=========================
    1. Python 3.7 or higher
    2. Additional packages:
           - numpy
           - sympy
           - matplotlib
           - scipy
           - pyqt5
           - joblib

Installing
=========================

You can use `pip` to install caldintav::

    pip install caldintav.tar.gz

from any directory or::

    python setup.py install

from the source directory.

Maybe you need to be the administrator to install the program. 

Running the CALDINTAV software
=========================

If the users have installed the CALDINTAV program as a Python package, it is necessary to
follow the next steps to run the program:

Open the Command Window (Terminal in Linux or Mac OS, Command Prompt in Windows
system)

Use the following command in the Command Window:

    caldintav3

or introducing the following commands in the Python shell:

    from caldintav import runs
    runs.run_gui()


For the Windows system, there is an executable program called caldintav.exe in the uncompressed folder, and to run the program, only double-click on the executable file

Support
=========================
If you encounter any issues or have questions, feel free to open an issue on GitHub or contact us at khanhnguyen.gia@upm.es



Licensing
----------

Copyright (c) 2018 The Python Packaging Authority

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
