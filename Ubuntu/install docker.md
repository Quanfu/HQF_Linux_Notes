# install Docker



> root@ubuntu:~# sudo apt-get update
```
Hit:1 http://us.archive.ubuntu.com/ubuntu bionic InRelease                                                
Get:2 http://security.ubuntu.com/ubuntu bionic-security InRelease [88.7 kB]                               
Get:3 http://us.archive.ubuntu.com/ubuntu bionic-updates InRelease [88.7 kB]       
Get:4 http://us.archive.ubuntu.com/ubuntu bionic-backports InRelease [74.6 kB]       
Fetched 252 kB in 2s (103 kB/s)                               
Reading package lists... Done
root@ubuntu:~# sudo apt-get remove docker docker-engine docker.io
Reading package lists... Done
Building dependency tree       
Reading state information... Done
Package 'docker-engine' is not installed, so not removed
Package 'docker' is not installed, so not removed
Package 'docker.io' is not installed, so not removed
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
```
> root@ubuntu:~# sudo apt-get install  docker.io

```
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  bridge-utils cgroupfs-mount containerd git git-man liberror-perl pigz runc ubuntu-fan
Suggested packages:
  aufs-tools btrfs-progs debootstrap docker-doc rinse zfs-fuse | zfsutils git-daemon-run | git-daemon-sysvinit git-doc git-el git-email git-gui gitk gitweb git-cvs git-mediawiki git-svn
The following NEW packages will be installed:
  bridge-utils cgroupfs-mount containerd docker.io git git-man liberror-perl pigz runc ubuntu-fan
0 upgraded, 10 newly installed, 0 to remove and 0 not upgraded.
Need to get 56.9 MB of archives.
After this operation, 291 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us.archive.ubuntu.com/ubuntu bionic/universe amd64 pigz amd64 2.4-1 [57.4 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu bionic/main amd64 bridge-utils amd64 1.5-15ubuntu1 [30.1 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu bionic/universe amd64 cgroupfs-mount all 1.4 [6,320 B]
Get:4 http://us.archive.ubuntu.com/ubuntu bionic-updates/universe amd64 runc amd64 1.0.0~rc7+git20190403.029124da-0ubuntu1~18.04.2 [1,903 kB]
Get:5 http://us.archive.ubuntu.com/ubuntu bionic-updates/universe amd64 containerd amd64 1.2.6-0ubuntu1~18.04.2 [19.4 MB]                                                                                        
Get:6 http://us.archive.ubuntu.com/ubuntu bionic-updates/universe amd64 docker.io amd64 18.09.7-0ubuntu1~18.04.4 [30.7 MB]                                                                                                                                                
Get:7 http://us.archive.ubuntu.com/ubuntu bionic/main amd64 liberror-perl all 0.17025-1 [22.8 kB]                                                                                                                                                                         
Get:8 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 git-man all 1:2.17.1-1ubuntu0.5 [803 kB]                                                                                                                                                              
Get:9 http://us.archive.ubuntu.com/ubuntu bionic-updates/main amd64 git amd64 1:2.17.1-1ubuntu0.5 [3,912 kB]                                                                                                                                                              
Get:10 http://us.archive.ubuntu.com/ubuntu bionic/main amd64 ubuntu-fan all 0.12.10 [34.7 kB]                                                                                                                                                                             
Fetched 56.9 MB in 4min 0s (237 kB/s)                                                                                                                                                                                                                                     
Preconfiguring packages ...
Selecting previously unselected package pigz.
(Reading database ... 164899 files and directories currently installed.)
Preparing to unpack .../0-pigz_2.4-1_amd64.deb ...
Unpacking pigz (2.4-1) ...
Selecting previously unselected package bridge-utils.
Preparing to unpack .../1-bridge-utils_1.5-15ubuntu1_amd64.deb ...
Unpacking bridge-utils (1.5-15ubuntu1) ...
Selecting previously unselected package cgroupfs-mount.
Preparing to unpack .../2-cgroupfs-mount_1.4_all.deb ...
Unpacking cgroupfs-mount (1.4) ...
Selecting previously unselected package runc.
Preparing to unpack .../3-runc_1.0.0~rc7+git20190403.029124da-0ubuntu1~18.04.2_amd64.deb ...
Unpacking runc (1.0.0~rc7+git20190403.029124da-0ubuntu1~18.04.2) ...
Selecting previously unselected package containerd.
Preparing to unpack .../4-containerd_1.2.6-0ubuntu1~18.04.2_amd64.deb ...
Unpacking containerd (1.2.6-0ubuntu1~18.04.2) ...
Selecting previously unselected package docker.io.
Preparing to unpack .../5-docker.io_18.09.7-0ubuntu1~18.04.4_amd64.deb ...
Unpacking docker.io (18.09.7-0ubuntu1~18.04.4) ...
Selecting previously unselected package liberror-perl.
Preparing to unpack .../6-liberror-perl_0.17025-1_all.deb ...
Unpacking liberror-perl (0.17025-1) ...
Selecting previously unselected package git-man.
Preparing to unpack .../7-git-man_1%3a2.17.1-1ubuntu0.5_all.deb ...
Unpacking git-man (1:2.17.1-1ubuntu0.5) ...
Selecting previously unselected package git.
Preparing to unpack .../8-git_1%3a2.17.1-1ubuntu0.5_amd64.deb ...
Unpacking git (1:2.17.1-1ubuntu0.5) ...
Selecting previously unselected package ubuntu-fan.
Preparing to unpack .../9-ubuntu-fan_0.12.10_all.deb ...
Unpacking ubuntu-fan (0.12.10) ...
Setting up git-man (1:2.17.1-1ubuntu0.5) ...
Setting up runc (1.0.0~rc7+git20190403.029124da-0ubuntu1~18.04.2) ...
Setting up liberror-perl (0.17025-1) ...
Setting up cgroupfs-mount (1.4) ...
Setting up containerd (1.2.6-0ubuntu1~18.04.2) ...
Created symlink /etc/systemd/system/multi-user.target.wants/containerd.service → /lib/systemd/system/containerd.service.
Setting up bridge-utils (1.5-15ubuntu1) ...
Setting up ubuntu-fan (0.12.10) ...
Created symlink /etc/systemd/system/multi-user.target.wants/ubuntu-fan.service → /lib/systemd/system/ubuntu-fan.service.
Setting up pigz (2.4-1) ...
Setting up git (1:2.17.1-1ubuntu0.5) ...
Setting up docker.io (18.09.7-0ubuntu1~18.04.4) ...
Adding group `docker' (GID 127) ...
Done.
Created symlink /etc/systemd/system/sockets.target.wants/docker.socket → /lib/systemd/system/docker.socket.
Processing triggers for systemd (237-3ubuntu10.33) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Processing triggers for ureadahead (0.100.0-21) ...
```

> root@ubuntu:~# sudo systemctl start docker

> root@ubuntu:~# sudo systemctl enable docker

```
Synchronizing state of docker.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable docker
```

> root@ubuntu:~# docker --version

```
Docker version 18.09.7, build 2d0083d
```

## Reference
[How To Install Docker On Ubuntu 18.04 Bionic Beaver](https://phoenixnap.com/kb/how-to-install-docker-on-ubuntu-18-04)   

