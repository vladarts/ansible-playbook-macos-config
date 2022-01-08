Ansible MacOS system configuration
==================================

Preparation
-----------

Pre-requisites:

- Xcode Command-Line Tools:

.. code-block:: bash

  xcode-select --install


- Homebrew

.. code-block:: bash

  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

- ansible

.. code-block:: bash

  brew install ansible

Execution
---------

Clone the repository:

.. code-block:: bash

  mkdir -p ${HOME}/dev/github.com/xxxbobrxxx/ansible-playbook-macos-config
  git clone git@github.com:xxxbobrxxx/system_config.git ${HOME}/dev/github.com/xxxbobrxxx/ansible-playbook-macos-config

Run the playbook:

.. code-block:: bash

  ansible-playbook ${HOME}/dev/github.com/xxxbobrxxx/ansible-playbook-macos-config/main.yaml

Links
-----

- https://github.com/pegasd/macos-config-playbook
- https://github.com/jeromegamez/ansible-macos-playbook
