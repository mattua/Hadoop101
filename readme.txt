1. Insall Cygwin if running on Windows

http://saphanatutorial.com/hadoop-installation-on-windows-7-using-cygwin/

Choose the second mirror in the list - the top one no longer works.

Ensure net.openssl, utils.dos2unix are selected

Answer yes to all the questions except whether to create a privileged account with different name to the default username "cyg_server".

Make sure the password you enter matches password requirements for the machine you are installing on

Make a note of the password ...

net start sshd starts the service

run ssh-user-config to set up user config

Enter passphrase (empty for no passphrase):
Enter same passphrase again:
*** Query: Do you want to use this identity to login to this machine? (yes/no) yes
*** Info: Adding to /home/matt.thomas/.ssh/authorized_keys
*** Query: Shall I create a SSH2 DSA identity file for you? (yes/no) no
*** Query: Shall I create a SSH2 ECDSA identity file for you? (yes/no) no
*** Query: Shall I create a (deprecated) SSH1 RSA identity file for you? (yes/no) no


2. Download hadoop binary from here
http://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-2.7.2/hadoop-2.7.2.tar.gz

3. Copy the tar file into your cygwin home/user folder
eg C:\cygwin64\home\matt.thomas

http://wiki.apache.org/hadoop/Hadoop2OnWindows