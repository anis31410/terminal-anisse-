To run a command as administrator (user "root"), use "sudo <command>".
See "man sudo_root" for details.

wilder@wilder-ThinkPad-T430s:~$ ls
Desktop    Downloads         Music     Public     Videos
Documents  examples.desktop  Pictures  Templates
wilder@wilder-ThinkPad-T430s:~$ ls .
Desktop    Downloads         Music     Public     Videos
Documents  examples.desktop  Pictures  Templates
wilder@wilder-ThinkPad-T430s:~$ ls -a
.              .cache     examples.desktop  Music             .ssh
..             .config    .gnupg            .pam_environment  Templates
.bash_history  Desktop    .ICEauthority     Pictures          Videos
.bash_logout   Documents  .local            .profile          .xinputrc
.bashrc        Downloads  .mozilla          Public
wilder@wilder-ThinkPad-T430s:~$ ls Pictures
wilder@wilder-ThinkPad-T430s:~$ ls /home/wilder
Desktop    Downloads         Music     Public     Videos
Documents  examples.desktop  Pictures  Templates
wilder@wilder-ThinkPad-T430s:~$ ls /home
wilder
wilder@wilder-ThinkPad-T430s:~$ ls ..
wilder
wilder@wilder-ThinkPad-T430s:~$ ls /bin
bash           fuser       nisdomainname  stty
brltty         fusermount  ntfs-3g        su
bunzip2        getfacl     ntfs-3g.probe  sync
busybox        grep        ntfscat        systemctl
bzcat          gunzip      ntfscluster    systemd
bzcmp          gzexe       ntfscmp        systemd-ask-password
bzdiff         gzip        ntfsfallocate  systemd-escape
bzegrep        hciconfig   ntfsfix        systemd-hwdb
bzexe          hostname    ntfsinfo       systemd-inhibit
bzfgrep        ip          ntfsls         systemd-machine-id-setup
bzgrep         journalctl  ntfsmove       systemd-notify
bzip2          kbd_mode    ntfsrecover    systemd-sysusers
bzip2recover   kill        ntfssecaudit   systemd-tmpfiles
bzless         kmod        ntfstruncate   systemd-tty-ask-password-agent
bzmore         less        ntfsusermap    tar
cat            lessecho    ntfswipe       tempfile
chacl          lessfile    open           touch
chgrp          lesskey     openvt         true
chmod          lesspipe    pidof          udevadm
chown          ln          ping           ulockmgr_server
chvt           loadkeys    ping4          umount
cp             login       ping6          uname
cpio           loginctl    plymouth       uncompress
dash           lowntfs-3g  ps             unicode_start
date           ls          pwd            vdir
dd             lsblk       rbash          wdctl
df             lsmod       readlink       which
dir            mkdir       red            whiptail
dmesg          mknod       rm             ypdomainname
dnsdomainname  mktemp      rmdir          zcat
domainname     more        rnano          zcmp
dumpkeys       mount       run-parts      zdiff
echo           mountpoint  sed            zegrep
ed             mt          setfacl        zfgrep
efibootdump    mt-gnu      setfont        zforce
efibootmgr     mv          setupcon       zgrep
egrep          nano        sh             zless
false          nc          sh.distrib     zmore
fgconsole      nc.openbsd  sleep          znew
fgrep          netcat      ss
findmnt        networkctl  static-sh
wilder@wilder-ThinkPad-T430s:~$ ls -l /bin
total 12440
-rwxr-xr-x 1 root root 1113504 avril  4  2018 bash
-rwxr-xr-x 1 root root  748968 août  29 09:57 brltty
-rwxr-xr-x 1 root root   34888 janv. 29  2017 bunzip2
-rwxr-xr-x 1 root root 2022480 déc.  12  2017 busybox
-rwxr-xr-x 1 root root   34888 janv. 29  2017 bzcat
lrwxrwxrwx 1 root root       6 févr.  1 10:54 bzcmp -> bzdiff
-rwxr-xr-x 1 root root    2140 janv. 29  2017 bzdiff
lrwxrwxrwx 1 root root       6 févr.  1 10:54 bzegrep -> bzgrep
-rwxr-xr-x 1 root root    4877 janv. 29  2017 bzexe
lrwxrwxrwx 1 root root       6 févr.  1 10:54 bzfgrep -> bzgrep
-rwxr-xr-x 1 root root    3642 janv. 29  2017 bzgrep
-rwxr-xr-x 1 root root   34888 janv. 29  2017 bzip2
-rwxr-xr-x 1 root root   14328 janv. 29  2017 bzip2recover
lrwxrwxrwx 1 root root       6 févr.  1 10:54 bzless -> bzmore
-rwxr-xr-x 1 root root    1297 janv. 29  2017 bzmore
-rwxr-xr-x 1 root root   35064 janv. 18  2018 cat
-rwxr-xr-x 1 root root   14328 avril 21  2017 chacl
-rwxr-xr-x 1 root root   63672 janv. 18  2018 chgrp
-rwxr-xr-x 1 root root   59608 janv. 18  2018 chmod
-rwxr-xr-x 1 root root   67768 janv. 18  2018 chown
-rwxr-xr-x 1 root root   10312 janv. 22  2018 chvt
-rwxr-xr-x 1 root root  141528 janv. 18  2018 cp
-rwxr-xr-x 1 root root  157224 déc.   2  2017 cpio
-rwxr-xr-x 1 root root  121432 janv. 25  2018 dash
-rwxr-xr-x 1 root root  100568 janv. 18  2018 date
-rwxr-xr-x 1 root root   76000 janv. 18  2018 dd
-rwxr-xr-x 1 root root   84776 janv. 18  2018 df
-rwxr-xr-x 1 root root  133792 janv. 18  2018 dir
-rwxr-xr-x 1 root root   72000 oct.  15 22:29 dmesg
lrwxrwxrwx 1 root root       8 févr.  1 10:54 dnsdomainname -> hostname
lrwxrwxrwx 1 root root       8 févr.  1 10:54 domainname -> hostname
-rwxr-xr-x 1 root root  170520 janv. 22  2018 dumpkeys
-rwxr-xr-x 1 root root   35000 janv. 18  2018 echo
-rwxr-xr-x 1 root root   51512 avril 26  2016 ed
-rwxr-xr-x 1 root root   18424 avril 21  2017 efibootdump
-rwxr-xr-x 1 root root   40056 avril 21  2017 efibootmgr
-rwxr-xr-x 1 root root      28 juil. 12  2017 egrep
-rwxr-xr-x 1 root root   30904 janv. 18  2018 false
-rwxr-xr-x 1 root root   10312 janv. 22  2018 fgconsole
-rwxr-xr-x 1 root root      28 juil. 12  2017 fgrep
-rwxr-xr-x 1 root root   64784 oct.  15 22:29 findmnt
-rwxr-xr-x 1 root root   35928 déc.  11 16:46 fuser
-rwsr-xr-x 1 root root   30800 août  11  2016 fusermount
-rwxr-xr-x 1 root root   23160 avril 21  2017 getfacl
-rwxr-xr-x 1 root root  219528 juil. 12  2017 grep
-rwxr-xr-x 1 root root    2301 avril 28  2017 gunzip
-rwxr-xr-x 1 root root    5927 avril 28  2017 gzexe
-rwxr-xr-x 1 root root  101560 avril 28  2017 gzip
-rwxr-xr-x 1 root root  196632 juin  22  2018 hciconfig
-rwxr-xr-x 1 root root   18504 janv. 31  2018 hostname
-rwxr-xr-x 1 root root  554104 févr. 26  2018 ip
-rwxr-xr-x 1 root root   63576 janv.  9 16:11 journalctl
-rwxr-xr-x 1 root root   10312 janv. 22  2018 kbd_mode
-rwxr-xr-x 1 root root   26704 mai   14  2018 kill
-rwxr-xr-x 1 root root  149688 nov.  12 22:54 kmod
-rwxr-xr-x 1 root root  170760 déc.   1  2017 less
-rwxr-xr-x 1 root root   10256 déc.   1  2017 lessecho
lrwxrwxrwx 1 root root       8 févr.  1 10:54 lessfile -> lesspipe
-rwxr-xr-x 1 root root   19856 déc.   1  2017 lesskey
-rwxr-xr-x 1 root root    8564 déc.   1  2017 lesspipe
-rwxr-xr-x 1 root root   67808 janv. 18  2018 ln
-rwxr-xr-x 1 root root  211528 janv. 22  2018 loadkeys
-rwxr-xr-x 1 root root   52664 janv. 25  2018 login
-rwxr-xr-x 1 root root   51280 janv.  9 16:11 loginctl
-rwxr-xr-x 1 root root  109232 nov.  30  2017 lowntfs-3g
-rwxr-xr-x 1 root root  133792 janv. 18  2018 ls
-rwxr-xr-x 1 root root   84048 oct.  15 22:29 lsblk
lrwxrwxrwx 1 root root       4 nov.  12 22:54 lsmod -> kmod
-rwxr-xr-x 1 root root   80056 janv. 18  2018 mkdir
-rwxr-xr-x 1 root root   67768 janv. 18  2018 mknod
-rwxr-xr-x 1 root root   43192 janv. 18  2018 mktemp
-rwxr-xr-x 1 root root   38952 oct.  15 22:29 more
-rwsr-xr-x 1 root root   43088 oct.  15 22:29 mount
-rwxr-xr-x 1 root root   14408 oct.  15 22:29 mountpoint
lrwxrwxrwx 1 root root      20 févr.  1 10:54 mt -> /etc/alternatives/mt
-rwxr-xr-x 1 root root   80512 déc.   2  2017 mt-gnu
-rwxr-xr-x 1 root root  137440 janv. 18  2018 mv
-rwxr-xr-x 1 root root  245872 mars   6  2018 nano
lrwxrwxrwx 1 root root      20 févr.  1 10:54 nc -> /etc/alternatives/nc
-rwxr-xr-x 1 root root   35312 mai   14  2018 nc.openbsd
lrwxrwxrwx 1 root root      24 févr.  1 10:54 netcat -> /etc/alternatives/netcat
-rwxr-xr-x 1 root root   43080 janv.  9 16:11 networkctl
lrwxrwxrwx 1 root root       8 févr.  1 10:54 nisdomainname -> hostname
-rwsr-xr-x 1 root root  146128 nov.  30  2017 ntfs-3g
-rwxr-xr-x 1 root root   10312 nov.  30  2017 ntfs-3g.probe
-rwxr-xr-x 1 root root   26728 nov.  30  2017 ntfscat
-rwxr-xr-x 1 root root   34920 nov.  30  2017 ntfscluster
-rwxr-xr-x 1 root root   34920 nov.  30  2017 ntfscmp
-rwxr-xr-x 1 root root   34928 nov.  30  2017 ntfsfallocate
-rwxr-xr-x 1 root root   43120 nov.  30  2017 ntfsfix
-rwxr-xr-x 1 root root   55416 nov.  30  2017 ntfsinfo
-rwxr-xr-x 1 root root   31928 nov.  30  2017 ntfsls
-rwxr-xr-x 1 root root   30824 nov.  30  2017 ntfsmove
-rwxr-xr-x 1 root root  116840 nov.  30  2017 ntfsrecover
-rwxr-xr-x 1 root root   88672 nov.  30  2017 ntfssecaudit
-rwxr-xr-x 1 root root   38944 nov.  30  2017 ntfstruncate
-rwxr-xr-x 1 root root   30744 nov.  30  2017 ntfsusermap
-rwxr-xr-x 1 root root   47752 nov.  30  2017 ntfswipe
lrwxrwxrwx 1 root root       6 févr.  1 10:54 open -> openvt
-rwxr-xr-x 1 root root   18872 janv. 22  2018 openvt
lrwxrwxrwx 1 root root      14 févr.  1 10:54 pidof -> /sbin/killall5
-rwsr-xr-x 1 root root   64424 mars   9  2017 ping
lrwxrwxrwx 1 root root       4 févr.  1 10:54 ping4 -> ping
lrwxrwxrwx 1 root root       4 févr.  1 10:54 ping6 -> ping
-rwxr-xr-x 1 root root   38904 sept. 12 01:03 plymouth
-rwxr-xr-x 1 root root  133432 mai   14  2018 ps
-rwxr-xr-x 1 root root   35000 janv. 18  2018 pwd
lrwxrwxrwx 1 root root       4 févr.  1 10:54 rbash -> bash
-rwxr-xr-x 1 root root   43192 janv. 18  2018 readlink
-rwxr-xr-x 1 root root      89 avril 26  2016 red
-rwxr-xr-x 1 root root   63704 janv. 18  2018 rm
-rwxr-xr-x 1 root root   43192 janv. 18  2018 rmdir
lrwxrwxrwx 1 root root       4 févr.  1 10:54 rnano -> nano
-rwxr-xr-x 1 root root   18760 déc.  30  2017 run-parts
-rwxr-xr-x 1 root root  109000 janv. 30  2018 sed
-rwxr-xr-x 1 root root   35512 avril 21  2017 setfacl
-rwxr-xr-x 1 root root   43144 janv. 22  2018 setfont
-rwxr-xr-x 1 root root   39288 août  24  2018 setupcon
lrwxrwxrwx 1 root root       4 févr.  1 10:54 sh -> dash
lrwxrwxrwx 1 root root       4 févr.  1 10:54 sh.distrib -> dash
-rwxr-xr-x 1 root root   35000 janv. 18  2018 sleep
-rwxr-xr-x 1 root root  139904 févr. 26  2018 ss
lrwxrwxrwx 1 root root       7 févr.  1 10:54 static-sh -> busybox
-rwxr-xr-x 1 root root   75992 janv. 18  2018 stty
-rwsr-xr-x 1 root root   44664 janv. 25  2018 su
-rwxr-xr-x 1 root root   35000 janv. 18  2018 sync
-rwxr-xr-x 1 root root  182352 janv.  9 16:11 systemctl
lrwxrwxrwx 1 root root      20 janv.  9 16:11 systemd -> /lib/systemd/systemd
-rwxr-xr-x 1 root root   10320 janv.  9 16:11 systemd-ask-password
-rwxr-xr-x 1 root root   14400 janv.  9 16:11 systemd-escape
-rwxr-xr-x 1 root root   84328 janv.  9 16:11 systemd-hwdb
-rwxr-xr-x 1 root root   14416 janv.  9 16:11 systemd-inhibit
-rwxr-xr-x 1 root root   18496 janv.  9 16:11 systemd-machine-id-setup
-rwxr-xr-x 1 root root   14408 janv.  9 16:11 systemd-notify
-rwxr-xr-x 1 root root   43080 janv.  9 16:11 systemd-sysusers
-rwxr-xr-x 1 root root   71752 janv.  9 16:11 systemd-tmpfiles
-rwxr-xr-x 1 root root   26696 janv.  9 16:11 systemd-tty-ask-password-agent
-rwxr-xr-x 1 root root  423312 janv. 21 17:38 tar
-rwxr-xr-x 1 root root   10104 déc.  30  2017 tempfile
-rwxr-xr-x 1 root root   88280 janv. 18  2018 touch
-rwxr-xr-x 1 root root   30904 janv. 18  2018 true
-rwxr-xr-x 1 root root  584072 janv.  9 16:11 udevadm
-rwxr-xr-x 1 root root   14328 août  11  2016 ulockmgr_server
-rwsr-xr-x 1 root root   26696 oct.  15 22:29 umount
-rwxr-xr-x 1 root root   35032 janv. 18  2018 uname
-rwxr-xr-x 1 root root    2301 avril 28  2017 uncompress
-rwxr-xr-x 1 root root    2762 janv. 22  2018 unicode_start
-rwxr-xr-x 1 root root  133792 janv. 18  2018 vdir
-rwxr-xr-x 1 root root   30800 oct.  15 22:29 wdctl
-rwxr-xr-x 1 root root     946 déc.  30  2017 which
-rwxr-xr-x 1 root root   26632 janv. 12  2018 whiptail
lrwxrwxrwx 1 root root       8 févr.  1 10:54 ypdomainname -> hostname
-rwxr-xr-x 1 root root    1937 avril 28  2017 zcat
-rwxr-xr-x 1 root root    1777 avril 28  2017 zcmp
-rwxr-xr-x 1 root root    5764 avril 28  2017 zdiff
-rwxr-xr-x 1 root root     140 avril 28  2017 zegrep
-rwxr-xr-x 1 root root     140 avril 28  2017 zfgrep
-rwxr-xr-x 1 root root    2131 avril 28  2017 zforce
-rwxr-xr-x 1 root root    5938 avril 28  2017 zgrep
-rwxr-xr-x 1 root root    2037 avril 28  2017 zless
-rwxr-xr-x 1 root root    1910 avril 28  2017 zmore
-rwxr-xr-x 1 root root    5047 avril 28  2017 znew
wilder@wilder-ThinkPad-T430s:~$ pwd
/home/wilder
wilder@wilder-ThinkPad-T430s:~$ cd
wilder@wilder-ThinkPad-T430s:~$ cd ..
wilder@wilder-ThinkPad-T430s:/home$ cd /opt
wilder@wilder-ThinkPad-T430s:/opt$ cd ../home/wilder
wilder@wilder-ThinkPad-T430s:~$ cd /usr/bin
wilder@wilder-ThinkPad-T430s:/usr/bin$ cd
wilder@wilder-ThinkPad-T430s:~$ cd ~
wilder@wilder-ThinkPad-T430s:~$ cd ~/Music
wilder@wilder-ThinkPad-T430s:~/Music$ 
