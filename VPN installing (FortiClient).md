# in this file you gonna lean how to configur and how to install the vpn (fortyClinet) in your kali linux
1. firts you need to download the file from authoriged
   - in my case i havce this [download link](https://www.fortinet.com/support/product-downloads)
2. and after you need to follow this code in terminal (you have multiple wats to install but in my case i have .rpm file so i need to first convert this in .deb file the i can install it )
   - insure you have alien (if not the) 'sudo install alien'
   - after follow this code
   - ```sudo alien --to-deb --scripts forticlient_vpn_7.4.3.1736_x86_64.rpm ``` ,
     ``` sudo dpkg -i forticlient_7.4.3.1736-2_amd64.deb ```
   - and now you successfully install the vpn client
3. and now the time is to configure the client for this you need to fill this information ![image](https://github.com/user-attachments/assets/5707d0dd-34e7-4e49-a65d-f30fd3ee3d5e)
4 . and after you have to connect using the username and password
 
