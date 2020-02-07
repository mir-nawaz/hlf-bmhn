# Build Multi-Host Network (BMHN)


# v1.4 Link
https://hyperledger-fabric.readthedocs.io/en/latest/whatis.html

## Open a terminal

`cd network/setup`

`sudo chmod u+x *.sh`

## Install Pre-Requisites & Validate

`./install-prereqs.sh`

Log out & Log back in - type exit and enter

`./validate-prereqs.sh`

## Install the Fabric binaries & images

`sudo -E ./install-fabric.sh`

Log out & Log back in

`./validate-fabric.sh`

## Install Hyperledger Explorer tool

`sudo -E ./install-explorer.sh`

Log out & Log back in

`./validate-explorer.sh`

## Install the Go Tools

`./install-gotools.sh`

## Install CA Server 

`./install-caserver.sh`

Log out & Log back in

`./validate-caserver.sh`

## Install Node JS - used by the utilities 

## To use some of the utilities Node JS is needed

`./install-node-utils.sh`

## Update the sample code

`cd network/setup`

`./update-git-repo.sh`

## Managing etc/hosts

Update the etc/hosts

`sudo ./manage_hosts.sh`

`cat /etc/hosts`






