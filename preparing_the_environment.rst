Preparing the Environment
=========================

Before we get too far into things, I'd like to first walk you through setting up
your development environment.

Since we're going to be hacking FreePBX code, we're obviously going to need a
FreePBX server to do work on as we make our way through this book.

Let's get to it!


Setting up VirtualBox
---------------------

Instead of installing FreePBX manually, compiling Asterisk, and all that good
stuff, we're instead going to run the officially supported `FreePBX Distro
<http://www.freepbx.org/freepbx-distro>`_, this way we don't have to go out of
our way to get things setup.

Since we're going to be running the official FreePBX distro, it also makes sense
that we'll want to install it in a virtual machine--this way we won't have to
install it on an actual computer anywhere, and waste resources.

`VirtualBox <https://www.virtualbox.org/>`_ is the perfect tool for this. It's
free, works on a wide variety of platforms, and is really simple to get setup.

So before we do anything else, download and install `VirtualBox
<https://www.virtualbox.org/wiki/Downloads>`_.

Now that you've got VirtualBox installed, let's create a new virtual machine! To
do this:

1. Click 'New'.
2. Type in a name for your new virtual machine. I usually use something like
   "FreePBX Beta 2.11.63-3". This way I know exactly which version of FreePBX
   I'm running in this virtual machine.
3. Under the 'Type' drop down menu, select 'Linux'.
4. Under the 'Version' drop down menu, select 'Other Linux'.
5. Press 'Next'.

On this next screen, you can give your virtual machine as much RAM as you want.
I'd recommend giving it about 2G of RAM--this way you can boot your FreePBX
development machine up and down quickly.

For the rest of this process, just press next and accept the defaults.

You should now how a new virtual machine ready to configure and use!


Preparing the Install
---------------------

Now before we install FreePBX on our new virtual machine, we need make two small
changes to our new virtual machine configuration.

And of course, let's not forget to download the FreePBX distro! You can download
this from the `FreePBX distro download page
<http://www.schmoozecom.com/distro-download.php>`_.

First off, open the configuration menu by right clicking the virtual machine
you created a moment ago, and click 'Settings'.

1. Visit the 'Storage' tab on the left, click the CD ROM icon, and on the right
   side of the screen, click the CD ROM icon again and select 'Choose a virtual
   CD/DVD disk file...' Now navigate to the ISO file you downloaded above, and
   select it. This is the equivalent of inserting a burned CD ROM into your
   virtual machine's CD ROM drive.

2. Now select the 'Network' tab on the left, and in the drop down menu labeled
   'Attached to:', select 'Bridged Adapter'. This means that your FreePBX
   virtual machine will get an IP address on your network, just like your
   development computer.

Now we're ready to do the install!


Installing FreePBX
------------------

TODO


Future Expectations
-------------------

TODO
