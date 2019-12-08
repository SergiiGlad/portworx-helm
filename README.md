# portworx-helm

https://www.ibm.com/cloud/blog/announcements/introducing-the-portworx-software-defined-storage-solution

---
## Portworx cluster after installed<

[pxctl status](images/49.png)

---
## This tells pgbench to create a database with 50 times, database size is now 800MB (50 x 16MB).

###### $ pgbench -i -s 50 pxdemo;

[pxctl status after add new db 800 Mb](images/14.png)

---
## Failing disk, detach gke-pd disk on one node.Add new one db which size 800 Mb

[after detach-disk](images/33.png)

---
## Attach disk back.Replicated and synchronous have done

[normal cluster](images/30.png)
