# Using Packer & Ansible to build a php7 LEMP Server On Cloud Native Infrastructure - Powered by Openstack.

This repository contains all the code required to take the Centos7 base image, and provision it with everything required to run a Nginx & PHP-fpm, along with php7. It will take the image, and store it in your OpenStack image repository, glance.

## Building

To run, simply run the following command:

```
$ packer build ./packer/template.json
```

## Further reading.

There is an online tutorial which contains more information: @TODO