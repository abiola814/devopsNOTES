Prerequisite
	1. Oracle VM Virtualbox
	2. Vagrant
	3. Vagrant plugins
		a. vagrant plugin install vagrant-hostmanager
		b. vagrant plugin install vagrant-vbguest
	4. Git bash or equivalent editor
	VM SETUP

		Clone source code.
		Cd into the repository.
		Switch to the local-setup branch.
		cd into vagrant/ Manual_provisioning.
		Bring up vm’s
		$ vagrant up
NOTE: Bringing up all the vm’s may take a long time based on various factors.
If vm setup stops in the middle run “vagrant up” command again.
INFO: All the vm’s hostname and /etc/hosts file entries will be automatically updated.
