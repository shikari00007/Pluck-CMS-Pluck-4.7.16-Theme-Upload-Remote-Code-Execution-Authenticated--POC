# Pluck-CMS-Pluck-4.7.16-Theme-Upload-Remote-Code-Execution-Authenticated-POC

* Exploit Author: Ashish Koli (Shikari)
* Vendor Homepage: https://github.com/pluck-cms/pluck
* Version: 4.7.16
* CVE: CVE-2022-26965
* About this:
* This script uploads shell.tar to the PluckCMS. An application will untar the 
* package which allows us to access Webshell.
* Usage : python3 exploit.py <IP> <Port> <Password> <Pluckcmspath>
* Example:  python3 exploit.py 127.0.0.1 80 admin /pluck
* POC Exploit: https://youtu.be/vWZITp_FTTc
