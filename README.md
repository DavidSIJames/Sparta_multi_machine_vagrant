# Sparta multi machine vagrant

## Description
the aim of this home is to create two virtual machines with different configurations using one Vangrantfile.

The virtual machines must also pass the tests set for them.

## Technology used
* virtualbox
* vagrant
* bash

## How to Download

1. if you do not have virtualbox download it [here](https://www.virtualbox.org/wiki/Downloads)

2. if you do not have vagrant installed download it [here](https://www.vagrantup.com/downloads.html)

3. If you do not have git installed follow this [guide](https://gist.github.com/derhuerst/1b15ff4652a867391f03)

4. In your browser, navigate to this [page](https://github.com/DavidSIJames/Sparta_multi_machine_vagrant)

5. Open your Terminal and navigate to where you want to clone the repo.

6. Once there, enter the following command to clone the repo:

	```terminal
	git clone git@github.com:DavidSIJames/Sparta_multi_machine_vagrant.git
  ```
7. once the repo has been cloned, cd into it using this command

	```terminal
	cd Sparta_multi_machine_vagrant/starter-code
	```
8. in the terminal enter the following command (this may take awhile):
  ```terminal
    vagrant up
  ```
9. When the process is complete enter this command into the terminal to ssh into the app vm:
  ```terminal
    vagrant ssh app
  ```
10. type ``exit`` into the terminal to exit the ssh

11. enter this command into the terminal to ssh into the db vm:
  ```terminal
    vagrant ssh db
  ```
## Challenges
no Challenges faced.

## Takeaway

This was a straight forward homework. the only issue is with setting up the mongod.conf file to have the correct settings on startup. the method s
