# vagrant-centos


## Install Vagrant on Ubuntu 20.04

![vagrant-virtualbox](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-virtualbox.png)

### prerequisites
* Install [Vagrant](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/vagrant/installation/vagrant_install.sh)
* Install [VirtualBox](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/vagrant/installation/vagrant_install.sh)

Create a directory `vagrant-centos-8`,
And change to **vagrant-centos-8**.

![mkdir](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/mkdir.png)

Now Opening the **VirtualBox** using `virtualbox` command

![open-virtualbox](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/open-virtualbox.png)

And the **VirtualBox** is Opening!

![virtualbox-page](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/virtualbox-page.png)

Next, initialize a new **Vagrantfile** using the `vagrant init` command, followed by the box you want to use.

Boxes are the package format for the Vagrant environments and are provider-specific. You can find a list of publicly available Vagrant Boxes on the Vagrant box catalog page.

![vagrant-centos-8-1](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_1.png)

list to see **Vagrantfile**

![vagrant-centos-8-2](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_2.png)

**Vagrantfile** is a Ruby file that describes how to configure and provision the virtual machine. You can open the **Vagrantfile** , read the comments, and make adjustments according to your needs.

Run the vagrant up command to create and configure the virtual machine as specified in the Vagrantfile:


![vagrant-centos-8-3](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_3.png)

![vagrant-centos-8-4](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_4.png)

![vagrant-centos-8-5](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_5.png)

**Vagrant** mounts the project directory at `/vagrant` in the *virtual machine*.
This allows you to work on your project’s files on your *host machine*.

![vagrant-centos-8-6](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_6.png)

To **ssh** into the virtual machine, run:

![vagrant-centos-8-7](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_7.png)

Checking **OS Version**

![vagrant-centos-8-8](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_8.png)

Checking **OS Distribution** in `Screenfetch`

![vagrant-centos-8-9](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_9.png)

You can stop the virtual machine with the following command:

![vagrant-centos-8-10](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_10.png)

Now, **vagrant-centos-8** poweroffed.

![vagrant-centos-8-11](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_11.png)

To destroy all resources created during the creation of the machine, enter:

![vagrant-centos-8-12](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_12.png)

Now, **vagrant-centos-8** destroyed.

![vagrant-centos-8-13](https://github.com/selvaraj-kuppusamy/vagrant-centos/blob/main/assets/vagrant-centos-8_13.png)

### conclusion
I shown you how to install ***Vagrant*** on **Ubuntu 20.04** and create a basic Vagrant project.

To find more information about **Vagrant** visit, the official [Vagrant documentation](https://www.vagrantup.com/docs) page.




