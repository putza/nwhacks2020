#############################################
Getting Started
#############################################


*************************************************
Python / Data Science Development Enviornments
*************************************************

Anaconda
==================================================

Anaconda Setup on Linux
---------------------------------------------------

.. code-block:: bash

    $ conda create --name MSGarage python=3.7
    $ conda install jupyter scipy pandas matplotlib scikit-learn seaborn pydotplus scikit-image opencv tensorflow graphviz
    $ conda activate MSGarage
    $ jupyter-notebook



*************************************************
Javascript Based Enviornments
*************************************************

Node.Js
==================================================

.. code-block:: bash

    curl -sL https://deb.nodesource.com/setup_12.x | sudo bash -
    sudo apt install nodejs
    sudo apt install npm

    node --version
    npm --version

    npm install create-react-app

Note: `npm install` can be used with the global option -g to create a system wide install. sudo privilege is needed in this case.



React
==================================================

.. code-block:: bash

    npm install create-react-app
    create-react-app my-app

    cd my-app/
    cd my-app/





React Native
==================================================

.. code-block:: bash

    npm install react-native-cli


Android Dev Kit
===================================================

Followed `Android Wave <https://androidwave.com/install-and-setup-react-native-on-ubuntu/>`_

.. code-block:: bash

    sudo add-apt-repository ppa:webupd8team/java
    sudo add-apt-repository ppa:webupd8team/java
    sudo apt install oracle-java8-installer

    sudo apt install oracle-java8-set-default
    javac -version

    
