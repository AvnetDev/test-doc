*****
Title
*****
---------
Sub-Title
---------
..
    This is a COMMENT to explain the following line is used to create a reference to a line of the document
.. _reference_label-section-1:

Section 1
=========

.. _section-1.1:

Section 1.1
^^^^^^^^^^^
..
    The following 1.1.1 section will render smaller text in VS code but same size text in readthedocs.io
Section 1.1.1
~~~~~~~~~~~~~
Yada yada yada YADA - This would be a paragraph

Inline code (Matlab) example:

.. code-block:: matlab

    function [y] = convert(x)
    	y = x;
    end

Inline shell command example:

.. code-block:: console

    rm -rf


Http link example: https://ultra96-pynq.readthedocs.io

Hyperlink to external page example: `Click me <https://www.avnet.com>`_

Reference to section in same document: :ref:`reference_label-section-1`

Reference to section in same document: :ref:`section-1.1`

Reference to a different .rst file: :doc:`./matt_page`

Reference to a different .rst with text: :doc:`Matt's page <./matt_page>`

**Bold**

*Italics*

Pictures:

..
    For '.. image::' height, scale, align are optional
.. image:: images/f5m.png
    :height: 200px
    :scale: 75%
    :align: center
    :alt: this is text for when your mouse hovers over the image

.. figure:: images/f5m.png
    :width: 200px
    :align: center
    :alt: alternate text it is indeed
    :figclass: align-center

    **figure** is like image but with a caption

This is an inline Math equation:

.. math:: y = \int_{a}^{b}{f(x) dx}

Ordered list:

1. item a
    1.1 item a.1
2. item b

Bullet list:

* item a
* item b

Movie time:

.. raw:: html

    <embed>
         <iframe width="560" height="315" src="https://www.youtube.com/watch?v=J_h2zxNdX0Q" frameborder="0" allowfullscreen></iframe>
         </br>
         </br>
    </embed>

.. note::  This is a **note** box.

.. warning:: note the space between the directive and the text

.. sidebar:: Sidebar Title
    :subtitle: Optional Sidebar Subtitle

    Subsequent indented lines comprise
    the body of the sidebar, and are
    interpreted as body elements.

+---------+---------+-----------+
| 1       |  2      |  3        |
+---------+---------+-----------+

+---------------------+---------+---+
|1                    |        2| 3 |
+---------------------+---------+---+

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
=====  =====  ======
