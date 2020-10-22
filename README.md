# Automated Setup of Software Development Environment
This is a sample project which is described in the blog post "Automated Setup of Software Development Environment" published on the [mimacom blog](https://blog.mimacom.com/automated-setup-of-software-development-environment/).


Before creating and starting the virtual machine, you could install a plugin called vagrant-vbguest by executing vagrant plugin install vagrant-vbguest. It takes care of installing the host's version of the Guest Additions on the guest system automatically.

Finally the new virtual machine is created and started by executing vagrant up in the directory containing your Ansbile and Vagrant configuration files. After the virtual machine is created, the provisioner is triggered automatically. This might take some time to finish (approx. 5-15 minutes).

Once this process ended, you need to restart the guest with vagrant reload. You should then see the Ubuntu login screen in a Virtualbox window. You can now log in by choosing the developer user with the password mimacom.

https://blog.mimacom.com/automated-setup-of-software-development-environment/
