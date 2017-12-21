# agm

AGM features + bash prompt facilities

# To install it

_Requirements_:

- bash

_Installation_:

- clone the repo
- run `./agm.sh setup`
- configure your prompt with `agm-configure`
    If your prompt were already updated, add --force

    ex:
        ```bash
        agm-configure --force
        ```

# My configuration

When I run those environment on my workstation, I'm setting several
things.

1. Add git-prompt.sh in /etc/profile.d

    Fedora:

    ```bash
    $ sudo cp/usr/share/doc/git-core-doc/contrib/completion/git-prompt.sh
    ```

    Ubuntu:

    Nothing to do. Already loaded if git is installed.

1. On the agm-configure, I'm selecting the chris2.prpt

    This one is a general prompt

    It is based on git function that needs to be loaded in your bashrc
