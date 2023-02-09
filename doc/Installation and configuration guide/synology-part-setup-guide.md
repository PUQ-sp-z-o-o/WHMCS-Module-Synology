# Synology part setup guide

#####  [Order now](https://panel.puqcloud.com/index.php?rp=/store/whmcs-module-synology) | [Dowload](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Synology/) | [FAQ](https://faq.puqcloud.com/)

Here are the initial steps of configuring Synology devices to prepare them for use with the WHMCS module.

<p class="callout info">At the beginning, you should prepare the appropriate domain with the correct DNS entries so that you can generate a correct SSL certificate for Your Synology NAS server. </p>

##### 1. Generate an SSL certificate for your domain.

Connect the certificate for all services that will be used in the server.(FTPS, System, Synology Drive, etc...)

[![image-1660043277546.png](https://doc.puq.info/uploads/images/gallery/2022-08/scaled-1680-/image-1660043277546.png)](https://doc.puq.info/uploads/images/gallery/2022-08/image-1660043277546.png)

##### 2. Make sure the partition is formatted in BTRFS

[![image-1660043720097.png](https://doc.puq.info/uploads/images/gallery/2022-08/scaled-1680-/image-1660043720097.png)](https://doc.puq.info/uploads/images/gallery/2022-08/image-1660043720097.png)

#####  

##### 3. Enable the user's home folder.

[![image-1660043845442.png](https://doc.puq.info/uploads/images/gallery/2022-08/scaled-1680-/image-1660043845442.png)](https://doc.puq.info/uploads/images/gallery/2022-08/image-1660043845442.png)

#####  

##### 4. Enable all necessary file services (ie: FTP, FTPS, SFTP, etc.).

[![image-1660043988444.png](https://doc.puq.info/uploads/images/gallery/2022-08/scaled-1680-/image-1660043988444.png)](https://doc.puq.info/uploads/images/gallery/2022-08/image-1660043988444.png)

##### 5. Create user groups with the necessary quotas and permissions.

[![image-1660043586117.png](https://doc.puq.info/uploads/images/gallery/2022-08/scaled-1680-/image-1660043586117.png)](https://doc.puq.info/uploads/images/gallery/2022-08/image-1660043586117.png)

[![image-1660043591654.png](https://doc.puq.info/uploads/images/gallery/2022-08/scaled-1680-/image-1660043591654.png)](https://doc.puq.info/uploads/images/gallery/2022-08/image-1660043591654.png)