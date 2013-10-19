linux-snippets
==============

collection of small linux scripts

switchOffGraphicsCard
---------------------

This small scripts switchs off your dedicated graphics card on boot-up. It's usefull to calm down noisy and heating notebooks.

**Installation & Usage**:
   * put the file into `/etc/init.d/`
   * run init.d setup command depending on your system (e.q. `update-rc.d` on ubuntu or `insserv` on opensuse)
   * now the switch gets off after boot (try it be running `./switchOffGraphicsCard` directly)
   
