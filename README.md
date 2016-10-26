# rdb-fullstack

Common code for the Relational Databases and Full Stack Fundamentals courses

## Prerequisites

* [VirtualBox](https://www.virtualbox.org/)
* [Vagrant](https://www.vagrantup.com/downloads.html)

## Setup dev environment

* clone the repo: `git clone https://github.com/mradenovic/fullstack-nanodegree-vm.git fullstack`
* cd into **vagrant** directory: `cd fullstack/vagrant`
* start virtual machine: `vagrant up`
* connect to virtual machine: `vagrant ssh`

## Projects

### Project: Tournament Results

Tournament Results is the fourth project built during completion of the [Udacity's](https://www.udacity.com/) Nanodegree program [Full Stack Web Developer](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004). To learn how it was built, check [Intro to Relational Databases](https://www.udacity.com/course/intro-to-relational-databases--ud197).


To run the test, [setup dev environment](#setup-dev-environment) first. You should get terminal prompt that looks something like this: `vagrant@vagrant-ubuntu-trusty-32:~$`. Once connected, run following commands:
* `cd /vagrant/tournament`
* `psql -f tournament.sql`
* `python tournament_test.py`
