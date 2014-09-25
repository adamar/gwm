GWM (Golang Workspace Manager)
=========

GWM is a lightweight workspace manager written entirely in Bash.

Please Note: GWM is not a version manager, if your looking for something more comprehensive
and feature packed please see https://github.com/moovweb/gvm

Installation
----

```sh
wget https://raw.githubusercontent.com/adamar/gwm/master/scripts/setup   
{Read the setup script before running}
chmod u+x setup  
./setup
```


Dependencies
----
* Git
* Bash (Newer than v3.0)


Usage
----

```sh
cd /home/user/golang/docker
gwm --init
{magic happens}
```


FAQ
-----------

Q: What does GWM actually do?  
A: Not much, it drops you into a subshell with some localised environment variables

Q: Where are packages put?  
A: The GOPATH is set to _src in the workspace.

