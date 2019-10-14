eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 172.20.164.200  netmask 255.255.255.0  broadcast 172.20.164.255
        inet6 fe80::a00:27ff:fe06:391d  prefixlen 64  scopeid 0x20<link>
        ether 08:00:27:06:39:1d  txqueuelen 1000  (Ethernet)
        RX packets 9068  bytes 639458 (624.4 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 28  bytes 2824 (2.7 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        
        
        
        
        
        lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 20  bytes 1116 (1.0 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 20  bytes 1116 (1.0 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        
        
        解釋下列資訊的意義:
mtu 1500
inet 172.17.0.1  
netmask 255.255.0.0  
broadcast 172.17.255.255
ether 02:42:a0:1e:82:96
```
```
問題1.IP位址==?  172.20.164.200 
問題2.mtu 1500  最大傳輸單元Maximum Transmission Unit  https://en.wikipedia.org/wiki/Maximum_transmission_unit
問題1.MAC address==實體網卡位址==>ether 08:00:27:2a:d5:62
問題1.broadcast address==https://en.wikipedia.org/wiki/Broadcast_address
      
問題1.
問題1.lo==localhost address=?

```
# ping 172.17.0.1

```

```
        
        
   ### linux實戰作業.md
```     
        root@kali:~# pwd
/root
root@kali:~# cd ..
root@kali:/# pwd
/
root@kali:/# LS
bash: LS: command not found
root@kali:/# ls
0     dev   initrd.img      lib64       mnt   root  srv  usr      vmlinuz.old
bin   etc   initrd.img.old  lost+found  opt   run   sys  var
boot  home  lib             media       proc  sbin  tmp  vmlinuz


