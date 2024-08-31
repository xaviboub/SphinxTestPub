Modificacions Sphinx
=====================

Per adaptar el format de lectura a l'estàndard **read the docs**, anar a aquesta web i instal.lar el format i configurar-lo segons convingui:
`ReadTheDocs <https://sphinx-rtd-theme.readthedocs.io/en/stable/>`_


Per introduir imatges
----------------------

* creem el directori "images" dins de la carpeta "source"
* dipositem allà als arxius amb les imatges que necessitem
* piquem el següent codi:

.. figure:: images/xml.png
    :align: right
    :alt: xml
    :scale: 30%

    Exemple de comentari a la imatge


.. code:: python

    .. figure:: images/xml.png
        :align: right
        :alt: xml
        :scale: 30%

        Exemple de comentari a la imatge


Per introduir requadres d'avís
--------------------------------

Hi ha requadres de diferents tipus. En tots ells és important seguir el format i els espaiats següents:

* Tipus Nota

.. note::

   Una **nota** d'Exemple

I el codi:

.. code:: python

    .. note::

       Una **nota** de Exemple


.. warning::

   Una **avís** d'Exemple

I el codi:

.. code:: python

    .. warning::

       Una **avís** de exemple

.. seealso::
   Exemple de **vegeu també**
    
   Línia2

I el codi:

.. code:: python

    .. seealso::
       Exemple de **vegeu també**
    
       Línia2


.. tip::
   Exemple de **truc**
    
I el codi:

.. code:: python

    .. tip::
       Exemple de **tip**


.. error::
   Exemple de **error**


.. admonition:: Títol personalitzat

    Exemple de **admonition**

I el codi:

.. code:: python

    .. admonition:: Títol personalitzat

    Exemple de **admonition**. 'notar que cal deixar una línia en blanc'





Per crear requadres de text en vermell
---------------------------------------

Un exemple és aquest: ``sphinx_rtd_theme`` 

Només cal posar el text entre aquestes cometes: `` (dues al principi i dues al final)


Per crear links a webs externes
--------------------------------

Per exemple, crearem un link a google.com:
`Google <https://www.google.com>`_

I el codi és aquest:

.. code:: python

    `Google <https://www.google.com>`_



Per crear tabuladors
----------------------

cal tenir l'extensió de tabuladors (posar referència)

.. tabs:: lang

    .. code-tab:: python

        print("Hello world")

    .. code-tab:: bash

        echo "Hello world"

i fer servir aquest codi:

.. code:: python

    .. tabs:: lang

        .. code-tab:: python

            print("Hello world")

        .. code-tab:: bash

            echo "Hello world"





