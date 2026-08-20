![[Task 1 - Front.png]]


2.) 
- Write down the ip addresses of each PC using the *ipconfig*  command on cmd
- in order to find the dns server, use *ipconfig /all*
- public DNS Server: 10.16.0.2 

3.) 
- install *Acrylic DNS Proxy* on PC1
- after installation, navigate to This PC/Program Files x86/acrylic/AcrylicHosts.txt and config.ini
- open the files as administrator in a text editor (notepad++)
- write the ip addresses in the AcrylicHosts.txt 
	- 10.16.48.43 netexperts.ph
	- 10.16.48.43 www.netexperts.ph
	- 10.16.48.1 r1.netexperts.ph
	- 10.16.48.43 ftp.netexperts.ph
	- 10.16.48.43 smb.netexperts.ph
	- 10.16.48.44 pc3.netexperts.ph
- for config.ini:
	- uncomment [GlobalSection] and comment the last one
	- [AllowedAddressesSection] IP1=10.16.48.

- make sure to go to services and stop and run acrylic





![[Task 1 - Back.png]]