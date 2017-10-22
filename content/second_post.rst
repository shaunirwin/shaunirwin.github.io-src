This is a super article !
#########################

:tags: example, tags, more tags
:date: 2017-10-22 08:14
:modified: 2017-10-22 23:01
:category: Another category
:author: Shaun Irwin
:summary:
    Multi-line metadata should be supported
    as well as **inline markup**.

Some content here !

This is a simple title
======================

And here comes the cool stuff_.

.. image:: {filename}/images/Sushi.jpg
    :height: 450 px
    :width: 600 px
    :alt: alternate text

.. image:: {filename}/images/Sushi_Macro.jpg
   :height: 450 px
   :width: 600 px
   :alt: alternate text

::

    >>> from ipdb import set_trace
    >>> set_trace()

.. code-block:: python

    print("Pelican is a static site generator.")

    def func(a):
        return a * 2

    for i in range(len(27)):
        x += func(i)

→ And now try with some utf8 hell: ééé

.. _stuff: http://books.couchdb.org/relax/design-documents/views