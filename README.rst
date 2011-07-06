Installation
============

* Copy the **cidadania-black** folder to the **_static** folder inside your sphinx
  documentation
* Set **html_theme** in your *conf.py* to "cidadania-black"
* Edit **teme.conf** and set your options:

  **showfooter** (true/false)
    Activate footer. This is the main difference between KR-Small theme and
    cidadania-black. Value can be *true* or *false*

  **showlinks** (true/false)
    Show the links widget in the footer. Value can be *true* or *false*.

  **showinfo** (true/false)
    Show the *about* information widget in the footer. Deactivating it will
    also deactivate the "Created with Sphinx" advertise. Value can be *true*
    or *false*

  **github_url** (url)
    Activates the top-right corner "Fork me on GitHub". If this variable is
    empty, the corner image will not be shown.

* Configure your links in the **links.html** file inside **cidadania-black**
* Configure your information in the **info.html** file inside
  **cidadania-black**

And now you're ready to rock!

Demonstration
=============

There is a project using this theme at:
`e-cidadania documentation <http://e-cidadania.readthedocs.org/>`_

Screenshots
===========

Three screenshots from de demonstration: index page, page with code, page created with autodoc

|Screenshot 1|_

.. |Screenshot 1| image:: http://github.com/oscarcp/cidadania-black/raw/master/screenshots/shot01-mini.png
.. _Screenshot 1: http://github.com/oscarcp/cidadania-black/raw/master/screenshots/shot01.png

|Screenshot 2|_

.. |Screenshot 2| image:: http://github.com/oscarcp/cidadania-black/raw/master/screenshots/shot02-mini.png
.. _Screenshot 2: http://github.com/oscarcp/cidadania-black/raw/master/screenshots/shot02.png

|Screenshot 3|_

.. |Screenshot 3| image:: http://github.com/oscarcp/cidadania-black/raw/master/screenshots/shot03-mini.png
.. _Screenshot 3: http://github.com/oscarcp/cidadania-black/raw/master/screenshots/shot03.png
