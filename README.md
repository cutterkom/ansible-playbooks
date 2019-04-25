# Some Basic Ansible Playbooks for R

- `install-r-and-r-packages.yml`: Installs R and some packages system-wide
- `install-r-and-shiny-server.yml`: Installs R, the ``shiny`` package (and others, if you want) and a [Shiny Server on Ubuntu](https://docs.rstudio.com/shiny-server/)
- ``install-r-and-shiny-server-allow-users-to-host.yml``: Installs R, packages and Shiny, **plus** allowing users to host their own apps in their home directory. Translates [the instructions in the Shiny Server Admin Guide to ansible](https://docs.rstudio.com/shiny-server/#let-users-manage-their-own-applications)
