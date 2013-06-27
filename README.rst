vbox_tests
==========

VirtualBox (Vagrant) testing for Plone Unified Installer

This is an experimental framework for running Plone Unified
Installer tests in a set of Vagrant-provisioned VirtualBoxes.

    ./runvbs.sh

runs the suite.

Each vb_* directory is a vagrant kit that provisions an environment
adequate to run the installer.

In each vb_* directory, the `install` files contains a Unified Installer
command line suitable for that OS.