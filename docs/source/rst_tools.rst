VS Code Installation for RST rendering
=======================================

Install the Software
---------------------

1. Install Pyton https://www.python.org/downloads/

.. image:: images/python_install.jpg

2. Add Python to your system path.

.. image:: images/python_path.jpg

3. Install Visual Studio Code (editor only) https://code.visualstudio.com/

.. image:: images/vscode_install.jpg

4. Open VS Code and install the **reStructuredText** extension

.. image:: images/vscode_rst_ext.jpg

File Preview/rendering
----------------------

1. Create a new file and copy/paste the following text.

::

  **Bullet List**
    * one 
    * two 
    * three

2. Save with a **.rst** file extension.

VS Code Preview pane should display a formatted list like this:

.. image:: images/bullets_formatted.jpg

.. note:: If VS Code does not show a rendered preview, observe any warnings/errors. You may need to open a Windows CMD shell and enter commands as as instructed by the warnings in VS Code preview.

.. note:: VS Code may prompt you for a conf.py for Sphinx. Choose the one that it suggests from your current directory.

.. image:: images/sphinx_conf.jpg

