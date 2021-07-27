Role Name
=========
ohmy

Requirements
------------

Role Variables
--------------
* `shell_user`: the user ZSH will be activated for
* `zsh_plugins`: list of plugins for zsh to load e.g. git zsh-autosuggestions
* `zplug_theme`: zplug theme to load e.g. dracula/zsh

Example Playbook
----------------

    - hosts: localhost
      connection: local
      roles:
         - { role: ck3mp3r.ohmy, shell_user: john, zsh_plugins: git zsh-autosuggestions, zplug_theme: dracula/zsh }

License
-------

MIT

Author Information
------------------

Christian Kemper | kemper.buzz
