# osmc-nfs-server-python3

Python3 script for setting up NFS-Server on OSMC, automount shares & manual shares. 

<h3>Install:</h3>

OSMC Stretch:
          
          sudo python3 nfs-server-setup.py
          
OSMC Buster:
          
          sudo python nfs-server-setup.py
   

<h3>Uninstall:</h3>

OSMC Stretch:

          sudo python3 uninstall-nfs-server.py
          
OSMC Buster:

          sudo python uninstall-nfs-server.py
          
Uninstall script removes server and reverts /etc/exports to default. 
