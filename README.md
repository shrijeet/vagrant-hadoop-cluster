vagrant-hadoop-cluster
======================

[Cloudera Manager](http://www.cloudera.com/content/cloudera/en/products/cloudera-manager.html)

------

    $ vagrant box add CentOS-6.3-x86_64-minimal http://dl.dropbox.com/s/0w7x9bhv98tp2me/CentOS-6.3-x86_64-minimal.box
    $ git clone git://github.com/shrijeet/vagrant-hadoop-cluster.git
    $ cd vagrant-hadoop-cluster
    $ vagrant up
    $ vagrant ssh manager
    [vagrant@hadoop-manager ~]$ wget http://archive.cloudera.com/cm4/installer/latest/cloudera-manager-installer.bin
    [vagrant@hadoop-manager ~]$ chmod +x cloudera-manager-installer.bin
    [vagrant@hadoop-manager ~]$ sudo ./cloudera-manager-installer.bin

Cloudera Manager
