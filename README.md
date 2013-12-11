openshift-pocketsphynx-ubuntu-cartridge
==========================

This cartridge use proot and ubuntu and install sphinx and pocketspinx and run LiveTranscriber.
openshift-ubuntu-cartridge
To log into ubuntu:

cd ubuntu;
./proot -r ubuntu -0 -b /dev -b /etc/resolv.conf -b /proc bash
