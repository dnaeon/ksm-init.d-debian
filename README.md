## KSM init.d script for Debian GNU/Linux

In order to use this script and have KSM enabled during boot-time, drop the *ksm* script into your */etc/init.d* directory.

Then enable the *ksm* script by running the following command:

	$ sudo update-rc.d ksm defaults
	
## Enabling KSM

	$ sudo service ksm start
	Enabling Kernel Samepage Merging.

## Disabling KSM

	$ sudo service ksm stop
	Disabling Kernel Samepage Merging.

## Getting status info

	% sudo service ksm status
	Kernel Samepage Merging is disabled.

