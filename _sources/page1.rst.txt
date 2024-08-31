Creació entorn virtual
========================

Dins del **directori on es vulgui creat el projecte**, cal crear un entorn virtual. Per això, cal fer:

1. Instal.lar l'entorn de virtualitzacio a la màquina virtual:
    sudo apt intall python3 -venv

2. crear l'entorn de virtualitzaciño dins de la carpeta del projecte
    python3 -m venv -venv

3. activar l'entorn de virtualitzacio. Cal fer-ho cada vegada que es comenci a treballa amb Sphinx
    source .venv/bin/activate

Instal.lar sphinx
-------------------

4. Instal.lar sphinx amb
    pip install sphinx

5. Iniciar un projecte sphinx amb
    sphinx-quickstart

això inicia unes preguntes prèvies a desplegar el projecte

Nota: accepta la llengua catalana. Cal posar **'ca'**

Nota: millor separar l'entorn **build** del **source**


Instal.lar el botó de copiar i tabuladors de codi
---------------------------------------------------

Aquestes extensions permeten que els requadres "code" que conetenen codi es pugui copiar el codi amb una icona de "copiar"

Dins de l'entorn de virtualització, cal entrar:

.. code:: bash

    pip install sphinx-copybutton

    pip install sphinx_code_tabs


Despŕes cal anar a l'arxiu ``conf.py`` i afegir aquestes entrades a les ``extensions``:


.. code:: bash

    extensions = ['sphinx_rtd_theme','sphinx_copybutton','sphinx_code_tabs']






