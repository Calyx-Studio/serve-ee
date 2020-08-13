# serve-ee
A script allowing for NGINX to serve 2 PHP apps one in a subdirectory in the other. It was developed for Vagrant/Homestead to serve ExpressionEngine and WordPress

Drag serve-store.sh file to  /Homestead/scripts/serve-store.sh and adjust the path to the secondary PHP app

In your homestead.yaml for the domain:

 map:  store.loc
      to:  /home/vagrant/Code/project/path/public
      type: store
