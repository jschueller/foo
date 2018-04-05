===================
Otfmi documentation
===================

Table of contents
=================

.. toctree::
    :maxdepth: 1

    README.rst

.. toctree::
    :maxdepth: 3

    api.rst

Some plot
=========

.. plot::

    import matplotlib.pyplot as plt

    x=[0,1,2,3,4,5]
    y=[8,5,1,9,7,3]

    fig = plt.figure()
    ax = fig.add_subplot(111)
    ax.plot(x, y, marker='.')


Examples
========

.. toctree::
    :maxdepth: 1

    foo.ipynb
