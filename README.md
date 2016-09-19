# Welcome To My MarkDown File.
![ABC](http://www.baidu.com/img/bdlogo.gif)

Ubuntu & Debian

	1) apt-get update && apt-get dist-upgrade (# This is optional, but recommended.#)
	2) wget https://raw.githubusercontent.com/huangguan0217/setup-ipsec-vpn/master/vpnsetup.sh    
	3) sudo sh vpnsetup.sh
   	4) nano -w vpnsetup.sh

CentOS & RHEL

	1) yum update (# This is optional, but recommended.#)
	2) wget https://raw.githubusercontent.com/huangguan0217/setup-ipsec-vpn/huangguan0217-patch-1/vpnsetup_centos.sh
	3) sudo sh vpnsetup_centos.sh
	4) nano -w vpnsetup.sh

System Requirements:
A newly created Amazon EC2 instance, using these AMIs: (See instructions)
	• Ubuntu 16.04 (Xenial), 14.04 (Trusty) or 12.04 (Precise)
	• Debian 8 (Jessie) EC2 Images
	• CentOS 7 (x86_64) with Updates HVM
	• CentOS 6 (x86_64) with Updates HVM
-OR-
A dedicated server or KVM/Xen-based Virtual Private Server (VPS), with the following OS:
 (Note: Starting with a freshly installed system is recommended)
	• Ubuntu 16.04 (Xenial), 14.04 (Trusty) or 12.04 (Precise)
	• Debian 8 (Jessie)
	• Debian 7 (Wheezy) » Not recommended. Requires this workaround to work.
	• CentOS / Red Hat Enterprise Linux (RHEL) 6 or 7

From <https://github.com/hwdsl2/setup-ipsec-vpn#ubuntu--debian> 

PLEASE NOTE: For Windows users, a one-time registry change is required if the VPN server and/or client is behind NAT (e.g. home router). In case you see Error 628, go to the "Security" tab of VPN connection properties, enable CHAP and disable MS-CHAP v2.




Disable the Password for Root Login

Once you have copied your SSH keys unto your server and ensured that you can log in with the SSH keys alone, you can go ahead and restrict the root login to only be permitted via SSH keys.

In order to do this, open up the SSH config file:

	• sudo nano /etc/ssh/sshd_config
Within that file, find the line that includes PermitRootLogin and modify it to ensure that users can only connect with their SSH key:

	• PermitRootLogin without-password
Put the changes into effect:

	• reload ssh
Digital Ocean Addendum

The Digital Ocean control panel allows you to add public keys to your new droplets when they're created. You can generate the SSH Key in a convenient location, such as the computer, and then upload the public key to the SSH key section.

Then, when you create a new VPS, you can choose to include that public key on the server. No root password will be emailed to you and you can log in to your new virtual private server from your chosen client. If you created a passphrase, you will be prompted to enter that upon login.
