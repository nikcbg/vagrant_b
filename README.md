# vagrant_b

### Purpose of the repository 
- The repository uses Ubuntu-nginx64 box already uploaded in `vagrant` cloud and sets mutlti-machine web01 and web02.

#### List of files in the repository

File name                            | File description 
------------------------------------ | --------------------------------------------------------------
`Vagrantfile` | file with script that defines machine and software requirements and sets mutlti-machine web01 and web02.


### How to use this repository. 
- Install `virtualbox` by following this [instructions](https://www.virtualbox.org/wiki/Downloads).
- Install `vagrant` by following this [instructions](https://www.vagrantup.com/docs/installation/).
- Clone the repository to your local computer: `git clone git@github.com:nikcbg/vagrant_b.git`.
- Go to the cloned repo on your computer: `cd vagrant_b`.
- After that execute the commands in the table below.

Command execution                    | Command outcome
------------------------------------ | --------------------------------------------------------------
`vagrant up` | to power up the nginx64 VM.
`vagrant ssh` | to log in to the nginx64 VM.


### TO DO:
- Check if you can `vagrant ssh` web01 and `vagrant ssh` web02

