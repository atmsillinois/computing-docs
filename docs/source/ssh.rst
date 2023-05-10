Access Keeling via ssh
======================

Keeling is the ATMS computing cluster that can be used for computing work.
When connecting off campus, the VPN must be used. Information on the CISCO
AnyConnect Virtual Private Network (VPN) is available
`here <https://techservices.illinois.edu/vpn-essentials/>`__.

The hostname for Keeling is:

.. code-block:: console

    keeling.earth.illinois.edu

Connecting via ssh on MacOS of Linux with terminal
--------------------------------------------------

Using the terminal, you can connect to Keeling by:

.. code-block:: console

    ssh -Y netID@keeling.earth.illinois.edu

Connecting via ssh on Windows
-----------------------------

.. todo:: Do people use Putty still? `here <https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html>`__

Graphical display
-----------------

In order to use a graphical display on Keeling, you must enable X Windows forwarding.
On MacOS, this requires XQuartz - an open-source project to develop X Window System.
Information regarding XQuartz can be found `here <https://www.xquartz.org/>`_.

.. todo:: What do people use on Windows? Xming `here <https://sourceforge.net/projects/xming/>`__?
