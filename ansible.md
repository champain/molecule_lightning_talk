# Test Your Ansible

A tale about making Molecule work for you.



## What is Ansible?

- IT automation
- Yaml
- RedHat Supported
- Bash for lazy developers


![ssssnake](images/snake.png)

Note:
- python-based



## What Ansible is _not_


### A programming language




## So how do you test it?


### Acceptance testing

A test conducted to determine if the requirements of a specification or contract are met.

Note:

- According to wikipedia


![](images/molecule.png)



## Molecule

A testing framework for Ansible


## Steps
- destroy
- dependency
- syntax
- create
- prepare
- converge
- idempotence
- lint
- side_effect
- verify
- destroy



## Drivers
- Docker
- VirtualBox
- AWS
- OpenStack


## Verifiers
- Testinfra
- Goss

Note:
- Testinfra is a lot like serverspec
- Goss is written in Go, looks tasty

## Virtualenv

It works! Use it!



### I thought this was easy

`molecule converge`



## Why I like it

* Repeatable
* Portable
* Verifiable
* Works with CI
* If your role uses it, I'm more likely to use your role




# Contact info
Jacob Castello
jacob.castello@excella.com
github.com/champain
