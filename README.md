# openstack_volume_mounting

1) mkfs -t ext4 -L amlevin1volume /dev/vdb
2) mount -L amlevin1volume /mnt
3) chmod +t /mnt
4) chmod a+w /mnt
5) Add the line `LABEL=amlevin1volume /mnt ext4 noatime,nodiratime,user_xattr,nofail    0       0` to the file /etc/fstab
