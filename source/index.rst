.. 这个是注释

我的第一个网站
=====================================

基于sphinx的网站搭建

安装
---------

`anaconda <https://www.anaconda.com/download/#macos>`_ ，sphinx，make，latex(miktex)

生成
--------

.. code-block:: bash
    
    make html
    echo "finished"

绘图
---------
利用matplotlib直接绘图

代码直接绘图
^^^^^^^^^^^^^

.. plot:: 
    :include-source:

    import numpy as np
    import matplotlib 
    import matplotlib.pyplot as plt
    x=np.linspace(-2*np.pi, 2*np.pi, 100)
    y=np.sin(x)
    plt.plot(x,y)
    plt.show()

从文件绘图
^^^^^^^^^^^^

.. plot:: test_plot.py 


数学公式
^^^^^^^^^^

.. math:: 

    a^2 + b^2 = c^2 \\
    \alpha^2 + \beta^2 = \gamma^2

加载图片
^^^^^^^^^^^

.. image:: https://www.anaconda.com/wp-content/themes/anaconda/images/logo-dark.png

.. figure:: https://www.anaconda.com/wp-content/themes/anaconda/images/logo-dark.png
    :align: center

    anconda库的logo

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
