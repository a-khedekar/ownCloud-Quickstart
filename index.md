# ownCloud Quickstart Guide
## Introduction
Welcome to the ownCloud quick start guide. ownCloud is free and open-source file synchronization and sharing solution. ownCloud provides accessibility through web browsers, Android and iOS app or a desktop client(Linux, MacOS, Windows). This guide explains how to install and configure ownCloud server as an administrator. It further explores on the ways you can access ownCloud server once it has been installed and configured as a admin or an user.

## Prerequisites 
ownCloud requires a web server, a database, and a PHP version to function properly. To find detailed software prerequisites [click here](https://doc.owncloud.org/server/9.1/admin_manual/installation/source_installation.html#prerequisites-label). 

## Install and Configure ownCloud Server
To successfully install ownCloud server let us start by installing individual dependencies in following steps.

#### Enable Yum Repositories
Firstly, you need to enable REMI and EPEL yum repositories in your system. Use following command to install RHEL 7.

```
rpm -Uvh http://dl.fedoraproject.org/pub/epel/7/x86_64/Packages/e/epel-release-7-11.noarch.rpm
rpm -Uvh http://rpms.famillecollet.com/enterprise/remi-release-7.rpm
```
