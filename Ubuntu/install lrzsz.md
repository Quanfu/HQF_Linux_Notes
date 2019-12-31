# Using Xshell upload and download the Linux server file XManager

XManage is a connection of windows and Linux software, including Xshell, Xftp, Xlpd and Xstart


FreeSurfer in the Linux server installed, XStart can log, where Protocol is the SSH


Open the Xshell login SSH


In windows and Linux to upload or download a file, in fact there is a very simple method is RZ,sz


First, you need to install the Ubuntu `rz.sz` (if not installed execute the following command, after installation please skip. Other versions of the Linux install the software itself)

```
sudo apt-get install lrzsz
```

Run the command `RZ`, is receiving the file, xshell will pop up the file selection dialog box, select the file dialog box is closed, the file will be uploaded to the current directory in Linux


Run the command `SZ` file is to send files to windows (save directory can be configured) than the FTP command much more convenient, and the server is not open FTP service.


However, the test found that RZ and SZ velocity is slow, so the SSHSecureShellClient connection with the server to upload and download files is the best choice！
