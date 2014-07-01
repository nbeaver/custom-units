=====================
Custom GNU units file
=====================

`GNU units`_ is a command-line unit calculator.
It is a tool with a long history, dating back to the Unix utility.
It lets you do things like checking to see if room-temperature hydrogen gas `can be treated classically`_ (it can)::

    You have: (h^3*(0.09 g/L)/(2amu))/(2*pi*(2amu)*k*273K)^(3/2)
    You want:
        Definition: 1.1302493e-05

This calculation is simple becase the definitions for Planck's constant, grams, liters, amu, Boltzmann's constant, and Kelvin are built in.

The default units library is extensive, but sometimes, of course, the default units are not enough.
GNU units makes it easy to define and use your own units via the text file ``~/.units`` in your home directory.
You can also run the default file and any custom units file like this::

    units -f '' -f /path/to/my-units.dat

My custom units file is `here`_.

.. _GNU units: https://www.gnu.org/software/units/
.. _can be treated classically: https://en.wikipedia.org/wiki/Thermal_de_Broglie_wavelength
.. _here: custom-units.txt
