# ArkRepo
Ark Survival Evolved Dedicated Server Guide with All DLC.

Introduction
==================

This is a doc on how to build an Ark Survival Evolved Server, with all DLCs installed using a shared cluster method for allowing Items, Dinos and players to transfer between world maps. I've tested this guide out multiple times and have my own running servers for Ark using the steps I've provided here.

Steps involved
==================

.. caution::

 This guide requires a basic understanding of Linux System Administration. Their are several concepts with regards to Linux that are being applied here including the creation of SystemD Units and modifying of Linux File Heirarchy for Ubuntu 18.04. These concepts I won't be going into much descussion here and it is assumed that you are aware of these concepts when you proceed with this guide. Please work with caution.

This guide will be following the guide found at https://survivetheark.com/index.php?/forums/topic/87419-guide-cluster-setup/ and information provided from https://survivetheark.com/index.php?/forums/topic/85463-scorched-earth-technicaldetail-faq-ongoing/ respectfully. 

For this build I used ``Ubuntu 18.04 LTS`` as my OS. This setup is a mixture of the ``Method 1`` used in the above setup with my own spin on it for use with modern Ubuntu 18.04, since 14.04 LTS (as referenced in the official Ark Documentation) has since been depreciated.

I've created an Ark Dedicated server with a shared Cluster ID using individual save file locations for each map. Uploaded items to the Obelisks will go to the Cluster save directory to be shared amoungst the maps. This includes the base game along with The Center, Scorched Earth, Ragnarok, Abberation, Extinction and Valguero maps. 

At the time of this writing the version of Ark was ``v303.1``, before the Genesis Expansion release. It is currently unknown whether you can transfer Items and Dinos from The Island map back to Scorched Earth though. Will test this out in future.

Full steps can be found at:

https://github.com/hubnet5116/ArkRepo/blob/master/index.rst
