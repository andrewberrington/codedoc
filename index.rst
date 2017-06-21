A301 Code
+++++++++

(source at `a301_code <https://github.com/a301-teaching/a301_code>`_)


A301 modules and packages
=========================


Examples
________

Some standalone scripts that are run as main programs i.e.::


week1.py
********

To run, do either::

  python week1.py

or::

  python -m a301examples.week1


.. automodule:: a301examples.week1
   :members:             

diff_lapse_toa.py
*****************

To run, do either::

  python a301examples.diff_lapse_toa.py

or::

  python -m a301examples.diff_lapse_toa.py


.. automodule:: a301examples.diff_lapse_toa
   :members:             

      
Radiation
_________
      
.. automodule:: a301lib.radiation
   :members:             

Utilities
_________
      
.. automodule:: a301utils.a301_readfile
   :members:             

Mapping
_______
      
.. automodule:: a301lib.geolocate
   :members:             
      
A301 Programs
=============

h5dump.py
_________

.. argparse::
   :ref: a301utils.h5dump.make_parser
   :prog: h5dump.py
