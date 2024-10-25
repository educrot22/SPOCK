.. _getting-started:

.. warning::
    You must be part of the SPECULOOS consortium  to download *SPOCK*.

Installation
-------------

Please follow the instructions below to install the package

Install *SPOCK* locally::

    git clone https://github.com/educrot22/SPOCK.git

    cd spock

    pip install -r requirements.txt

    pip install .

Using *SPOCK*
---------------

To use *SPOCK* you will need to be part of the SPECULOOS consortium and have access to:
 * the SPECULOOS server,
 * the Portal,
 * the Cambridge Archive,
 * the SPECULOOS WG6 spread sheet
 * the SSO HUB,
 * SNO reduction PC.

Then follow the procedure:

1. the first step is to add a *password.csv* file in the folder: "your_SPOCK_path/SPOCK/credentials/".

2. the second step is to connect to the Liège VPN to have access to all functions of *SPOCK*

3. open `SPOCK_app.ipyn` in a jupyter notebook and click on ``run all cells`` to check everything is working fine.

Contact Elsa Ducrot for more details (educrot@uliege.be)

Upgrading
-------------

- In a terminal in *SPOCK* source code folder::

    git stash
    git pull


More details on *SPOCK*
--------------------------

*SPOCK* is presented in more details in `Sebastian et al. 2020 <http://arxiv.org/abs/2011.02069>`_.