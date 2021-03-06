Linux 系统下使用 Phalcon 开发工具（Phalcon Developer Tools on Linux）
=====================================================================

These steps will guide you through the process of installing Phalcon Developer Tools for Linux.

预备知识（Prerequisites）
-------------------------
The Phalcon PHP extension is required to run Phalcon Tools. If you haven't installed it yet, please see the :doc:`Installation <install>`
section for instructions.

下载（Download）
----------------
You can download a cross platform package containing the developer tools from the Download_ section. Also you can clone it from Github_.

Open a terminal and type the command below:

.. code-block:: bash

    git clone git://github.com/phalcon/phalcon-devtools.git

.. figure:: ../_static/img/linux-1.png
   :align: center

Then enter the folder where the tools were cloned and execute ". ./phalcon.sh", (don't forget the dot at beginning of the command):

.. code-block:: bash

    cd phalcon-devtools/

    . ./phalcon.sh

.. figure:: ../_static/img/linux-2.png
   :align: center

Create a symbolink link to the phalcon.php script:

.. code-block:: bash

    ln -s ~/phalcon-devtools/phalcon.php /usr/bin/phalcon

    chmod ugo+x /usr/bin/phalcon

Congratulations you now have Phalcon tools installed!

相关指南（Related Guides）
^^^^^^^^^^^^^^^^^^^^^^^^^^
* :doc:`Using Developer Tools <tools>`
* :doc:`Installation on Windows <wintools>`
* :doc:`Installation on Mac <mactools>`

.. _Download: http://phalconphp.com/download
.. _Github: https://github.com/phalcon/phalcon-devtools
