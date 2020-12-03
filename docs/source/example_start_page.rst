*****
Title
*****
---------
Sub-Title
---------
..
    This is a COMMENT to explain the following line is used to create a reference to a line of the document
.. _section-1:

Section 1
=========

.. _section-1.1:

Section 1.1
^^^^^^^^^^^
Section 1.1.1
~~~~~~~~~~~~~
Yada yada yada

Some inline code (Matlab) example:

.. code-block:: matlab

    function [y] = convert(x)
    	y = x;
    end

Some inline shell commands example:

.. code-block:: console

    rm -rf


Http link example: https://ultra96-pynq.readthedocs.io

Hyperlink to external page example: `Click me <https://www.avnet.com>`_

Reference to section in same document: :ref:`section-1`

Reference to section in same document: :ref:`section-1.1`

**Bold**

*Italics*

Pictures:

.. image:: images/f5m.png
    :align: center

.. image:: images/f5m.png
    :align: left

.. image:: images/f5m.png
    :align: right

This is an inline Math equation:

.. math:: y = \int_{a}^{b}{f(x) dx}

Ordered list:

1. item a
    1.1 item a.1
2. item b

Bullet list:

* item a
* item b
