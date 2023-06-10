# Using Vagrant on your personal computer

## The tools
There are multiple tools out there that can help you create and manage virtual environments (notice that we use the term “virtual environment” here, as such environemnt is not necessarily a VM. Technologies using containerization allow one to manage virtual environments as well).
We are using two tools at school: VirtualBox and Vagrant.

**VirtualBox** is a Virtual Machine provider. The virtual machines themselves will be spawned using VirtualBox. VirtualBox is free and lightweight, which make it a perfect choice for us.

**Vagrant** is a tool that sits on top of a VM provider. Again, we chose to use VirtualBox as a provider, but other providers exist out there and Vagrant offers the possibilty to use dfferent providers (More info [here](https://developer.hashicorp.com/vagrant/docs/providers "Title").). Just like VirtualBox, we choose to use Vagrant because it is free, reliable and well maintained. Keep in mind that the purpose here is to use Virtual environments, and both VirtualBox and Vagrant are just means to achieve this purpose.
