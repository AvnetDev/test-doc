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

Common Issues
-------------

Sphinx ReadTheDocsTheme not installed
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
The following error means that your conf.py file references a readthedocs theme that is not installed. Sphinx uses the theme to render your .rst as .html the way it will appear on readthedocs.org.
::

  Error
  Command failed: "C:\Users\Cecile\AppData\Local\Programs\Python\Python39\python.exe" -m sphinx -b html . "c:\Users\Cecile\Documents\Otava\Reference Design\DTRXX_TRX_Card\rfsoc-board-docs\docs\source\_build\html"
  WARNING: html_static_path entry '_static' does not exist

  Theme error:
  sphinx_rtd_theme is no longer a hard dependency since version 1.4.0. Please install it manually.(pip install sphinx_rtd_theme)

  Error: Command failed: "C:\Users\Cecile\AppData\Local\Programs\Python\Python39\python.exe" -m sphinx -b html . "c:\Users\Cecile\Documents\Otava\Reference Design\DTRXX_TRX_Card\rfsoc-board-docs\docs\source\_build\html"
  WARNING: html_static_path entry '_static' does not exist

**To resolve this:** open a Windows CMD shell and manually install the rtd theme for Sphinx using ``pip install sphinx_rtd_theme``

Preview Not Working
^^^^^^^^^^^^^^^^^^^^
If your preview is not working in Visual Studio, try the following.

1) Closing the .rst file, then close Visual Studio. 
2) From Windows Explorer, open your .rst file.
3) VS may prompt you for a **conf.py for Sphinx**. Choose the file associated with your project (VS usually suggests it for you).

.. image:: images/sphinx_conf.jpg

4) Click the Preview button in VS.

