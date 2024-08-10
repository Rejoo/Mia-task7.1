Hello world
To run a command as administrator (user "root"), use "sudo <command>".
See "man sudo_root" for details.

bash: /home/areej-maher/.bashrc: line 1: syntax error near unexpected token `('
bash: /home/areej-maher/.bashrc: line 1: `e# ~/.bashrc: executed by bash(1) for non-login shells.'
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ pwd
/home/areej-maher
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls
Desktop  Documents  Downloads  -l  mia7.2  Music  Pictures  Public  snap  Templates  Videos
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ mkdir Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls
Desktop  Documents  Downloads  -l  mia7.2  Mia7.2  Music  Pictures  Public  snap  Templates  Videos
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ cd Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ cd Mia7.2/
bash: cd: Mia7.2/: No such file or directory
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ pwd
/home/areej-maher/Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ ls
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ touch Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ ls
Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ nano Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ cat Mia7.2
Hello Mia!

areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ nano Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ cat
^C  
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ cat Mia7.2
Hello Mia!
Welcome Here !!

areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ echo Hello Mia
Hello Mia
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ ls
Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ rm Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ ls
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/Mia7.2$ cd ..
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls
Desktop  Documents  Downloads  -l  mia7.2  Mia7.2  Music  Pictures  Public  snap  Templates  Videos
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ rm Mia7.2/
rm: cannot remove 'Mia7.2/': Is a directory
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ rm --help
Usage: rm [OPTION]... [FILE]...
Remove (unlink) the FILE(s).

  -f, --force           ignore nonexistent files and arguments, never prompt
  -i                    prompt before every removal
  -I                    prompt once before removing more than three files, or
                          when removing recursively; less intrusive than -i,
                          while still giving protection against most mistakes
      --interactive[=WHEN]  prompt according to WHEN: never, once (-I), or
                          always (-i); without WHEN, prompt always
      --one-file-system  when removing a hierarchy recursively, skip any
                          directory that is on a file system different from
                          that of the corresponding command line argument
      --no-preserve-root  do not treat '/' specially
      --preserve-root[=all]  do not remove '/' (default);
                              with 'all', reject any command line argument
                              on a separate device from its parent
  -r, -R, --recursive   remove directories and their contents recursively
  -d, --dir             remove empty directories
  -v, --verbose         explain what is being done
      --help        display this help and exit
      --version     output version information and exit

By default, rm does not remove directories.  Use the --recursive (-r or -R)
option to remove each listed directory, too, along with all of its contents.

To remove a file whose name starts with a '-', for example '-foo',
use one of these commands:
  rm -- -foo

  rm ./-foo

Note that if you use rm to remove a file, it might be possible to recover
some of its contents, given sufficient expertise and/or time.  For greater
assurance that the contents are truly unrecoverable, consider using shred(1).

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Full documentation <https://www.gnu.org/software/coreutils/rm>
or available locally via: info '(coreutils) rm invocation'
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ man rm
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls
Desktop  Documents  Downloads  -l  mia7.2  Mia7.2  Music  Pictures  Public  snap  Templates  Videos
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ rm -r Mia7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ man ls
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls -l
total 52
drwxr-xr-x 3 areej-maher areej-maher 4096 Aug 10 21:11 Desktop
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Documents
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Downloads
-rw-r--r-- 1 areej-maher areej-maher 9546 Aug 10 21:18 -l
drwxrwxr-x 4 areej-maher areej-maher 4096 Aug 10 20:57 mia7.2
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Music
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Pictures
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Public
drwx------ 4 areej-maher areej-maher 4096 Aug 10 21:00 snap
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Templates
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Videos
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls -a
.   .bash_history  .bashrc  .config  Documents	-l	  .local  Music     .profile  snap  Templates
..  .bash_logout   .cache   Desktop  Downloads	.lesshst  mia7.2  Pictures  Public    .ssh  Videos
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls -l -a
total 96
drwxr-x--- 16 areej-maher areej-maher 4096 Aug 10 21:18 .
drwxr-xr-x  3 root        root        4096 Aug 10 20:28 ..
-rw-------  1 areej-maher areej-maher  603 Aug 10 21:01 .bash_history
-rw-r--r--  1 areej-maher areej-maher  220 Mar 31 10:41 .bash_logout
-rw-r--r--  1 areej-maher areej-maher 3788 Aug 10 20:59 .bashrc
drwx------ 10 areej-maher areej-maher 4096 Aug 10 20:31 .cache
drwx------ 11 areej-maher areej-maher 4096 Aug 10 21:03 .config
drwxr-xr-x  3 areej-maher areej-maher 4096 Aug 10 21:11 Desktop
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Documents
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Downloads
-rw-r--r--  1 areej-maher areej-maher 9546 Aug 10 21:18 -l
-rw-------  1 areej-maher areej-maher   20 Aug 10 21:18 .lesshst
drwx------  4 areej-maher areej-maher 4096 Aug 10 20:29 .local
drwxrwxr-x  4 areej-maher areej-maher 4096 Aug 10 20:57 mia7.2
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Music
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Pictures
-rw-r--r--  1 areej-maher areej-maher  807 Mar 31 10:41 .profile
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Public
drwx------  4 areej-maher areej-maher 4096 Aug 10 21:00 snap
drwx------  2 areej-maher areej-maher 4096 Aug 10 20:29 .ssh
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Templates
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Videos
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls -l -r
total 52
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Videos
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Templates
drwx------ 4 areej-maher areej-maher 4096 Aug 10 21:00 snap
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Public
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Pictures
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Music
drwxrwxr-x 4 areej-maher areej-maher 4096 Aug 10 20:57 mia7.2
-rw-r--r-- 1 areej-maher areej-maher 9546 Aug 10 21:18 -l
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Downloads
drwxr-xr-x 2 areej-maher areej-maher 4096 Aug 10 20:29 Documents
drwxr-xr-x 3 areej-maher areej-maher 4096 Aug 10 21:11 Desktop
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ pwd
/home/areej-maher
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ cd ..
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/home$ ls
areej-maher
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/home$ cd ..
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/$ ls
bin		   boot   dev  home  lib64		lost+found  mnt  proc  run   sbin.usr-is-merged  srv	   sys	usr
bin.usr-is-merged  cdrom  etc  lib   lib.usr-is-merged	media	    opt  root  sbin  snap		 swap.img  tmp	var
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/$ cd dev/
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/dev$ ls
acpi_thermal_rel  dri	       hwrng	input  loop-control  nvidiactl	       ptmx	 snd	 tty15	tty28  tty40  tty53  tty9	ttyS2	ttyS4	     vcs1   vcsu1	 zfs
autofs		  drm_dp_aux0  i2c-0	kmsg   mapper	     nvidia-modeset    pts	 stderr  tty16	tty29  tty41  tty54  ttyprintk	ttyS20	ttyS5	     vcs2   vcsu2
block		  drm_dp_aux1  i2c-1	kvm    mcelog	     nvidia-uvm        random	 stdin	 tty17	tty3   tty42  tty55  ttyS0	ttyS21	ttyS6	     vcs3   vcsu3
bsg		  ecryptfs     i2c-10	log    media0	     nvidia-uvm-tools  rfkill	 stdout  tty18	tty30  tty43  tty56  ttyS1	ttyS22	ttyS7	     vcs4   vcsu4
btrfs-control	  fb0	       i2c-11	loop0  mei0	     nvme0	       rtc	 tpm0	 tty19	tty31  tty44  tty57  ttyS10	ttyS23	ttyS8	     vcs5   vcsu5
bus		  fd	       i2c-2	loop1  mem	     nvme0n1	       rtc0	 tpmrm0  tty2	tty32  tty45  tty58  ttyS11	ttyS24	ttyS9	     vcs6   vcsu6
char		  freefall     i2c-3	loop2  mqueue	     nvme0n1p1	       sda	 tty	 tty20	tty33  tty46  tty59  ttyS12	ttyS25	udmabuf      vcsa   vfio
console		  full	       i2c-4	loop3  mtd	     nvme0n1p2	       sda1	 tty0	 tty21	tty34  tty47  tty6   ttyS13	ttyS26	uhid	     vcsa1  vga_arbiter
core		  fuse	       i2c-5	loop4  mtd0	     nvme0n1p3	       sda2	 tty1	 tty22	tty35  tty48  tty60  ttyS14	ttyS27	uinput	     vcsa2  vhci
cpu		  gpiochip0    i2c-6	loop5  mtd0ro	     nvme0n1p4	       sda3	 tty10	 tty23	tty36  tty49  tty61  ttyS15	ttyS28	urandom      vcsa3  vhost-net
cpu_dma_latency   hidraw0      i2c-7	loop6  net	     nvram	       sda4	 tty11	 tty24	tty37  tty5   tty62  ttyS16	ttyS29	userfaultfd  vcsa4  vhost-vsock
cuse		  hidraw1      i2c-8	loop7  ng0n1	     port	       sg0	 tty12	 tty25	tty38  tty50  tty63  ttyS17	ttyS3	userio	     vcsa5  video0
disk		  hpet	       i2c-9	loop8  null	     ppp	       shm	 tty13	 tty26	tty39  tty51  tty7   ttyS18	ttyS30	v4l	     vcsa6  video1
dma_heap	  hugepages    initctl	loop9  nvidia0	     psaux	       snapshot  tty14	 tty27	tty4   tty52  tty8   ttyS19	ttyS31	vcs	     vcsu   zero
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/dev$ cd /
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/$ cd ~
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ cd /
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/$ cd bin 
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/bin$ ls
'['				      foo2zjs			   ld.gold			      POST			       tee
 aa-enabled			      foo2zjs-icc2ps		   ld.so			      powerprofilesctl		       telnet
 aa-exec			      foo2zjs-pstops		   less				      ppdc			       tempfile
 aa-features-abi		      foo2zjs-wrapper		   lessecho			      ppdhtml			       test
 aconnect			      foomatic-rip		   lessfile			      ppdi			       tic
 acpidbg			      fprintd-delete		   lesskey			      ppdmerge			       tificc
 add-apt-repository		      fprintd-enroll		   lesspipe			      ppdpo			       time
 addpart			      fprintd-list		   lexgrog			      pphs			       timedatectl
 addr2line			      fprintd-verify		   libnetcfg			      pr			       timeout
 airscan-discover		      free			   link				      precat			       tload
 alsabat			      ftp			   linkicc			      preconv			       tnftp
 alsaloop			      funzip			   linux32			      preunzip			       toe
 alsamixer			      fuser			   linux64			      prezip			       top
 alsatplg			      fusermount		   linux-boot-prober		      prezip-bin		       touch
 alsaucm			      fusermount3		   linux-check-removal		      prime-select		       tput
 amidi				      fwupdmgr			   linux-update-symlinks	      prime-supported		       tr
 amixer				      fwupdtool			   linux-version		      printafm			       trace-cmd
 apg				      gamemoded			   listres			      printenv			       tracepath
 apgbfm				      gamma4scanimage		   ln				      printer-profile		       tracker3
 aplay				      gapplication		   lnstat			      printf			       tracker3-daemon
 aplaymidi			      gatttool			   loadkeys			      prlimit			       tracker3-endpoint
 apport-bug			      gcalccmd			   loadunimap			      pro			       tracker3-export
 apport-cli			      gcore			   locale			      prove			       tracker3-extract
 apport-collect			      gcr-viewer		   locale-check			      prtstat			       tracker3-help
 apport-unpack			      gcr-viewer-gtk4		   localectl			      ps			       tracker3-import
 appres				      gdb			   localedef			      ps2ascii			       tracker3-index
 appstreamcli			      gdb-add-index		   logger			      ps2epsi			       tracker3-info
 apropos			      gdbtui			   login			      ps2pdf			       tracker3-reset
 apt				      gdbus			   loginctl			      ps2pdf12			       tracker3-search
 apt-add-repository		      gdk-pixbuf-csource	   logname			      ps2pdf13			       tracker3-sparql
 apt-cache			      gdk-pixbuf-pixdata	   look				      ps2pdf14			       tracker3-sql
 apt-cdrom			      gdk-pixbuf-thumbnailer	   lowntfs-3g			      ps2pdfwr			       tracker3-status
 apt-config			      gdm-config		   lp				      ps2ps			       tracker3-tag
 aptdcon			      gdmflexiserver		   lpoptions			      ps2ps2			       transicc
 apt-extracttemplates		      gdm-screenshot		   lpq				      ps2txt			       transset
 apt-ftparchive			      gencat			   lpr				      psfaddtable		       troff
 apt-get			      geqn			   lprm				      psfgettable		       true
 apt-key			      GET			   lpstat			      psfstriptable		       truncate
 apt-mark			      getconf			   ls				      psfxtable			       trust
 apt-sortpkgs			      getent			   lsattr			      psicc			       tset
 ar				      getfacl			   lsblk			      pslog			       tsort
 arch				      getkeycodes		   lsb_release			      pstree			       tty
 arecord			      getopt			   lscpu			      pstree.x11		       turbostat
 arecordmidi			      gettext			   lshw				      ptar			       tzselect
 arm2hpdl			      gettext.sh		   lsinitramfs			      ptardiff			       ua
 as				      ghostscript		   lsipc			      ptargrep			       ubuntu-advantage
 aseqdump			      ginstall-info		   lslocks			      ptx			       ubuntu-bug
 aseqnet			      gio			   lslogins			      pw-cat			       ubuntu-core-launcher
 aspell				      gio-querymodules		   lsmem			      pw-cli			       ubuntu-distro-info
 aspell-import			      gipddecode		   lsmod			      pw-config			       ubuntu-drivers
 atobm				      gjs			   lsns				      pwd			       ubuntu-report
 awk				      gjs-console		   lsof				      pw-dot			       ubuntu-security-status
 axfer				      gkbd-keyboard-display	   lspci			      pw-dsdplay		       ucf
 b2sum				      glib-compile-schemas	   lspgpot			      pw-dump			       ucfq
 baobab				      gnome-calculator		   lspower			      pwdx			       ucfr
 base32				      gnome-characters		   lsusb			      pw-encplay		       uclampset
 base64				      gnome-clocks		   lwp-download			      pw-link			       ucs2any
 basename			      gnome-control-center	   lwp-dump			      pw-loopback		       udevadm
 basenc				      gnome-disk-image-mounter	   lwp-mirror			      pw-metadata		       udisksctl
 bash				      gnome-disks		   lwp-request			      pw-mididump		       ul
 bashbug			      gnome-extensions		   lzcat			      pw-midiplay		       umax_pp
 bc				      gnome-font-viewer		   lzcmp			      pw-midirecord		       umount
 bdftopcf			      gnome-help		   lzdiff			      pw-mon			       uname
 bdftruncate			      gnome-keyring		   lzegrep			      pw-play			       unattended-upgrade
 bitmap				      gnome-keyring-3		   lzfgrep			      pw-profiler		       unattended-upgrades
 bluemoon			      gnome-keyring-daemon	   lzgrep			      pw-record			       uncompress
 bluetoothctl			      gnome-language-selector	   lzless			      pw-reserve		       unexpand
 bluetooth-sendto		      gnome-logs		   lzma				      pw-top			       unicode_start
 bmtoa				      gnome-power-statistics	   lzmainfo			      py3clean			       unicode_stop
 boltctl			      gnome-session		   lzmore			      py3compile		       uniq
 bpftrace			      gnome-session-inhibit	   m17n-db			      py3versions		       unity-scope-loader
 bpftrace-aotrt			      gnome-session-properties	   m2300w			      pybabel			       unlink
 brltty				      gnome-session-quit	   m2300w-wrapper		      pybabel-python3		       unlzma
 brltty-atb			      gnome-shell		   m2400w			      pydoc3			       unmkinitramfs
 brltty-clip			      gnome-shell-extension-tool   man				      pydoc3.12			       unshare
 brltty-ctb			      gnome-shell-test-tool	   mandb			      pygettext3		       unsquashfs
 brltty-hid			      gnome-system-monitor	   manpath			      pygettext3.12		       unxz
 brltty-ktb			      gnome-terminal		   man-recode			      pygmentize		       unzip
 brltty-lscmds			      gnome-terminal.real	   mapscrn			      pyserial-miniterm		       unzipsfx
 brltty-morse			      gnome-terminal.wrapper	   markdown-it			      pyserial-ports		       unzstd
 brltty-trtxt			      gnome-text-editor		   mawk				      python3			       update-alternatives
 brltty-ttb			      gnome-thumbnail-font	   mbimcli			      python3.12		       update-desktop-database
 brltty-tune			      gnome-www-browser		   mbim-network			      pzstd			       update-manager
 broadwayd			      gold			   mcookie			      qmicli			       update-mime-database
 browse				      gp-archive		   md5sum			      qmi-firmware-update	       update-notifier
 btattach			      gpasswd			   md5sum.textutils		      qmi-network		       upower
 btmgmt				      gp-collect-app		   mdig				      qpdldecode		       uptime
 btmon				      gp-display-html		   memhog			      quirks-handler		       usb-devices
 busctl				      gp-display-src		   memusage			      ranlib			       usbhid-dump
 busybox			      gp-display-text		   memusagestat			      rbash			       usbip
 bwrap				      gpg			   mesa-overlay-control.py	      rctest			       usbipd
 calibrate_ppa			      gpg-agent			   mesg				      rdma			       usb_printerid
 canberra-gtk-play		      gpgconf			   migratepages			      readelf			       usbreset
 cancel				      gpg-connect-agent		   migrate-pubring-from-classic-gpg   readlink			       users
 captoinfo			      gpgparsemail		   migspeed			      realpath			       utmpdump
 cat				      gpgsm			   mimeopen			      red			       uuidgen
 catman				      gpgsplit			   mimetype			      rename.ul			       uuidparse
 cd-create-profile		      gpgtar			   min12xxw			      rendercheck		       varlinkctl
 cd-fix-profile			      gpgv			   mkdir			      renice			       vcs-run
 cd-iccdump			      gpg-wks-client		   mkfifo			      reset			       vdir
 cd-it8				      gpic			   mkfontdir			      resizecons		       vi
 c++filt			      gprof			   mkfontscale			      resizepart		       view
 chacl				      gprofng			   mk_modmap			      resolvectl		       viewres
 chage				      gpu-manager		   mknod			      rev			       vim.tiny
 chardet			      grdctl			   mksquashfs			      rfcomm			       vmstat
 chardetect			      grep			   mktemp			      rgrep			       vmwarectrl
 chattr				      gresource			   mmcli			      rm			       vstp
 chcon				      groff			   mokutil			      rmdir			       w
 check-language-support		      grog			   monitor-sensor		      rnano			       wall
 chfn				      grops			   more				      routel			       watch
 chgrp				      grotty			   mount			      rpcgen			       watchgnupg
 chmod				      groups			   mountpoint			      rrsync			       wc
 choom				      growpart			   mousetweaks			      rstart			       wdctl
 chown				      grub-editenv		   mpris-proxy			      rstartd			       wget
 chrt				      grub-file			   mpstat			      rsync			       whatis
 chsh				      grub-fstest		   mscompress			      rsync-ssl			       whereis
 chvt				      grub-glue-efi		   msexpand			      rtla			       which
 cifsiostat			      grub-kbdcomp		   mt				      rtstat			       which.debianutils
 ciptool			      grub-menulst2cfg		   mt-gnu			      runcon			       whiptail
 ckbcomp			      grub-mkfont		   mtr				      run-parts			       who
 cksum				      grub-mkimage		   mtrace			      run-with-aspell		       whoami
 clear				      grub-mklayout		   mtr-packet			      rview			       whoopsie
 clear_console			      grub-mknetdir		   mv				      rygel			       whoopsie-preferences
 cloud-id			      grub-mkpasswd-pbkdf2	   namei			      sadf			       wireplumber
 cloud-init			      grub-mkrelpath		   nano				      sane-find-scanner		       word-list-compress
 cloud-init-per			      grub-mkrescue		   nautilus			      sar			       wpa_passphrase
 cmp				      grub-mkstandalone		   nautilus-autorun-software	      sar.sysstat		       wpctl
 codepage			      grub-mount		   nautilus-sendto		      savelog			       wpexec
 col				      grub-render-label		   nawk				      sbattach			       write
 colcrt				      grub-script-check		   nc				      sbkeysync			       X
 colormgr			      grub-syslinux2cfg		   nc.openbsd			      sbsiglist			       X11
 colrm				      gs			   neqn				      sbsign			       x11perf
 column				      gsbj			   netaddr			      sbvarsign			       x11perfcomp
 comm				      gsdj			   netcat			      sbverify			       x86_64
 corelist			      gsdj500			   networkctl			      scanimage			       x86_64-linux-gnu-addr2line
 cp				      gsettings			   networkd-dispatcher		      scp			       x86_64-linux-gnu-ar
 cpan				      gslj			   newgrp			      scp-dbus-service		       x86_64-linux-gnu-as
 cpan5.38-x86_64-linux-gnu	      gslp			   ngettext			      screendump		       x86_64-linux-gnu-c++filt
 cpio				      gsnd			   nice				      script			       x86_64-linux-gnu-cpp
 cpp				      gst-device-monitor-1.0	   nisdomainname		      scriptlive		       x86_64-linux-gnu-cpp-13
 cpp-13				      gst-discoverer-1.0	   nl				      scriptreplay		       x86_64-linux-gnu-dwp
 cpupower			      gst-inspect-1.0		   nm				      sdiff			       x86_64-linux-gnu-elfedit
 c_rehash			      gst-launch-1.0		   nm-applet			      sdptool			       x86_64-linux-gnu-gold
 crontab			      gst-play-1.0		   nmcli			      seahorse			       x86_64-linux-gnu-gp-archive
 csplit				      gstreamer-codec-install	   nm-connection-editor		      sed			       x86_64-linux-gnu-gp-collect-app
 ctstat				      gst-stats-1.0		   nm-online			      select-default-iwrap	       x86_64-linux-gnu-gp-display-html
 cupstestppd			      gst-tester-1.0		   nmtui			      select-editor		       x86_64-linux-gnu-gp-display-src
 cut				      gst-typefind-1.0		   nmtui-connect		      sensible-browser		       x86_64-linux-gnu-gp-display-text
 cvt				      gtbl			   nmtui-edit			      sensible-editor		       x86_64-linux-gnu-gprof
 cvtsudoers			      gted			   nmtui-hostname		      sensible-pager		       x86_64-linux-gnu-gprofng
 dash				      gtf			   nohup			      sensible-terminal		       x86_64-linux-gnu-ld
 date				      gtk4-broadwayd		   notify-send			      seq			       x86_64-linux-gnu-ld.bfd
 dbus-cleanup-sockets		      gtk4-builder-tool		   nproc			      session-migration		       x86_64-linux-gnu-ld.gold
 dbus-daemon			      gtk4-encode-symbolic-svg	   nroff			      sessreg			       x86_64-linux-gnu-nm
 dbus-monitor			      gtk4-launch		   nsenter			      setarch			       x86_64-linux-gnu-objcopy
 dbus-run-session		      gtk4-path-tool		   nslookup			      setfacl			       x86_64-linux-gnu-objdump
 dbus-send			      gtk4-query-settings	   nstat			      setfont			       x86_64-linux-gnu-pkgconf
 dbus-update-activation-environment   gtk4-rendernode-tool	   nsupdate			      setkeycodes		       x86_64-linux-gnu-pkg-config
 dbus-uuidgen			      gtk4-update-icon-cache	   ntfs-3g			      setleds			       x86_64-linux-gnu-ranlib
 dbxtool			      gtk-builder-tool		   ntfs-3g.probe		      setlogcons		       x86_64-linux-gnu-readelf
 dc				      gtk-encode-symbolic-svg	   ntfscat			      setmetamode		       x86_64-linux-gnu-size
 dconf				      gtk-launch		   ntfscluster			      setpci			       x86_64-linux-gnu-strings
 dd				      gtk-query-settings	   ntfscmp			      setpriv			       x86_64-linux-gnu-strip
 ddstdecode			      gtk-update-icon-cache	   ntfsdecrypt			      setsid			       x86_energy_perf_policy
 deallocvt			      gunzip			   ntfsfallocate		      setterm			       xargs
 debconf			      gzexe			   ntfsfix			      setupcon			       xauth
 debconf-apt-progress		      gzip			   ntfsinfo			      setxkbmap			       xbiff
 debconf-communicate		      h2ph			   ntfsls			      sftp			       xbrlapi
 debconf-copydb			      h2xs			   ntfsmove			      sg			       xcalc
 debconf-escape			      hardlink			   ntfsrecover			      sh			       xclipboard
 debconf-set-selections		      hbpldecode		   ntfssecaudit			      sha1sum			       xclock
 debconf-show			      hciattach			   ntfstruncate			      sha224sum			       xcmsdb
 debian-distro-info		      hciconfig			   ntfsusermap			      sha256sum			       xconsole
 deb-systemd-helper		      hcitool			   ntfswipe			      sha384sum			       xcursorgen
 deb-systemd-invoke		      hd			   numactl			      sha512sum			       xcutsel
 delpart			      head			   numastat			      shasum			       xdg-dbus-proxy
 delv				      HEAD			   numfmt			      showconsolefont		       xdg-desktop-icon
 desktop-file-edit		      heif-thumbnailer		   nvidia-bug-report.sh		      showkey			       xdg-desktop-menu
 desktop-file-install		      helpztags			   nvidia-cuda-mps-control	      showrgb			       xdg-email
 desktop-file-validate		      hex2hcd			   nvidia-cuda-mps-server	      shred			       xdg-icon-resource
 df				      hexdump			   nvidia-debugdump		      shuf			       xdg-mime
 dh_bash-completion		      hipercdecode		   nvidia-detector		      size			       xdg-open
 dh_installxmlcatalogs		      host			   nvidia-ngx-updater		      skill			       xdg-screensaver
 dh_perl_openssl		      hostid			   nvidia-persistenced		      slabtop			       xdg-settings
 diff				      hostname			   nvidia-powerd		      sleep			       xdg-user-dir
 diff3				      hostnamectl		   nvidia-settings		      slogin			       xdg-user-dirs-gtk-update
 dig				      hp-align			   nvidia-sleep.sh		      slxdecode			       xdg-user-dirs-update
 dir				      hp-check			   nvidia-smi			      smproxy			       xditview
 dircolors			      hp-clean			   nvidia-xconfig		      snap			       xdpyinfo
 dirmngr			      hp-colorcal		   oakdecode			      snapctl			       xdriinfo
 dirmngr-client			      hp-config_usb_printer	   obexctl			      snapfuse			       xedit
 dirname			      hp-doctor			   objcopy			      snice			       Xephyr
 distro-info			      hp-firmware		   objdump			      soelim			       xev
 dmesg				      hp-info			   oclock			      software-properties-gtk	       xeyes
 dnsdomainname			      hp-levels			   od				      sort			       xfd
 domainname			      hp-logcapture		   oem-getlogs			      sotruss			       xfontsel
 do-release-upgrade		      hp-makeuri		   on_ac_power			      spa-acp-tool		       xgamma
 dpkg				      hp-pkservice		   oomctl			      spa-inspect		       xgc
 dpkg-deb			      hp-plugin			   open				      spa-json-dump		       xhost
 dpkg-divert			      hp-plugin-ubuntu		   openssl			      spa-monitor		       xinit
 dpkg-maintscript-helper	      hp-probe			   openvt			      spa-resample		       xinput
 dpkg-query			      hp-query			   opldecode			      spd-conf			       xkbbell
 dpkg-realpath			      hp-scan			   orca				      spd-say			       xkbcomp
 dpkg-split			      hp-setup			   orca-dm-wrapper		      spdsend			       xkbevd
 dpkg-statoverride		      hp-testpage		   os-prober			      speaker-test		       xkbprint
 dpkg-trigger			      hp-timedate		   p11-kit			      speech-dispatcher		       xkbvleds
 driverless			      hwe-support-status	   pager			      spice-vdagent		       xkbwatch
 driverless-fax			      i386			   paperconf			      splain			       xkeystone
 du				      ibus			   partx			      split			       xkill
 dumpkeys			      ibus-daemon		   passwd			      splitfont			       xload
 dvipdf				      ibus-setup		   paste			      sprof			       xlogo
 dwp				      ibus-table-createdb	   patch			      sqfscat			       xlsatoms
 eatmydata			      iceauth			   pathchk			      sqfstar			       xlsclients
 ec2metadata			      ico			   pdb3				      ss			       xlsfonts
 echo				      iconv			   pdb3.12			      ssh			       xmag
 ed				      id			   pdf2dsc			      ssh-add			       xman
 editor				      iecset			   pdf2ps			      ssh-agent			       xmessage
 editres			      ijs_pxljr			   pdfattach			      ssh-argv0			       xmodmap
 efibootdump			      im-config			   pdfdetach			      ssh-copy-id		       xmore
 efibootmgr			      im-launch			   pdffonts			      ssh-keygen		       Xorg
 egrep				      inetutils-telnet		   pdfimages			      ssh-keyscan		       xprop
 eject				      info			   pdfinfo			      sss_ssh_authorizedkeys	       xqxdecode
 elfedit			      infobrowser		   pdfseparate			      sss_ssh_knownhostsproxy	       xrandr
 enc2xs				      infocmp			   pdfsig			      startx			       xrdb
 encguess			      infotocap			   pdftocairo			      stat			       xrefresh
 enchant-2			      inputattach		   pdftohtml			      static-sh			       x-session-manager
 enchant-lsmod-2		      install			   pdftoppm			      stdbuf			       xset
 env				      install-info		   pdftops			      strace			       xsetmode
 envsubst			      instmodsh			   pdftotext			      strace-log-merge		       xsetpointer
 eog				      intel-virtual-output	   pdfunite			      streamzip			       xsetroot
 eps2eps			      ionice			   peekfd			      strings			       xsetwacom
 eqn				      iostat			   perf				      strip			       xsm
 esc-m				      ip			   perl				      stty			       xstdcmap
 eutp				      ipcmk			   perl5.38.2			      su			       xsubpp
 evince				      ipcrm			   perl5.38-x86_64-linux-gnu	      sudo			       x-terminal-emulator
 evince-previewer		      ipcs			   perlbug			      sudoedit			       xvidtune
 evince-thumbnailer		      ippfind			   perldoc			      sudoreplay		       xvinfo
 ex				      ipptool			   perli11ndoc			      sum			       Xwayland
 expand				      iptables-xml		   perlivp			      switcherooctl		       xwd
 expiry				      ischroot			   perlthanks			      sync			       xwininfo
 expr				      isdv4-serial-debugger	   pf2afm			      systemctl			       xwud
 factor				      isdv4-serial-inputattach	   pfbtopfa			      systemd			       x-www-browser
 faillog			      ispell-wrapper		   pgrep			      systemd-ac-power		       xxd
 fallocate			      join			   pic				      systemd-analyze		       xz
 false				      journalctl		   pico				      systemd-ask-password	       xzcat
 fc-cache			      jpgicc			   piconv			      systemd-cat		       xzcmp
 fc-cat				      jq			   pidof			      systemd-cgls		       xzdiff
 fc-conflist			      jsondiff			   pidstat			      systemd-cgtop		       xzegrep
 fc-list			      jsonpatch			   pidwait			      systemd-confext		       xzfgrep
 fc-match			      json-patch-jsondiff	   pinentry			      systemd-creds		       xzgrep
 fc-pattern			      jsonpointer		   pinentry-curses		      systemd-cryptenroll	       xzless
 fc-query			      json_pp			   pinentry-gnome3		      systemd-cryptsetup	       xzmore
 fc-scan			      jsonschema		   pinentry-x11			      systemd-delta		       yelp
 fc-validate			      kbdinfo			   ping				      systemd-detect-virt	       yes
 fgconsole			      kbd_mode			   ping4			      systemd-escape		       ypdomainname
 fgrep				      kbxutil			   ping6			      systemd-firstboot		       zcat
 file				      kernel-install		   pinky			      systemd-hwdb		       zcmp
 file2brl			      kerneloops-submit		   pipewire			      systemd-id128		       zdiff
 find				      kill			   pipewire-aes67		      systemd-inhibit		       zdump
 findmnt			      killall			   pipewire-avb			      systemd-machine-id-setup	       zegrep
 firefox			      kmod			   pipewire-pulse		      systemd-mount		       zenity
 flock				      kmodsign			   pkaction			      systemd-notify		       zfgrep
 fmt				      l2ping			   pkcheck			      systemd-path		       zforce
 fold				      l2test			   pkcon			      systemd-repart		       zgrep
 fonttosfnt			      laptop-detect		   pkexec			      systemd-run		       zip
 foo2ddst			      last			   pkgconf			      systemd-socket-activate	       zipcloak
 foo2ddst-wrapper		      lastb			   pkg-config			      systemd-stdio-bridge	       zipdetails
 foo2hbpl2			      lastlog			   pkill			      systemd-sysext		       zipgrep
 foo2hbpl2-wrapper		      lavadecode		   pkmon			      systemd-sysusers		       zipinfo
 foo2hiperc			      lcf			   pkttyagent			      systemd-tmpfiles		       zipnote
 foo2hiperc-wrapper		      ld			   pl2pm			      systemd-tty-ask-password-agent   zipsplit
 foo2hp				      ldapadd			   pldd				      systemd-umount		       zjsdecode
 foo2hp2600-wrapper		      ldapcompare		   plog				      tabs			       zless
 foo2lava			      ldapdelete		   plymouth			      tac			       zmore
 foo2lava-wrapper		      ldapexop			   pmap				      tail			       znew
 foo2oak			      ldapmodify		   pnm2ppa			      tapestat			       zstd
 foo2oak-wrapper		      ldapmodrdn		   pod2html			      tar			       zstdcat
 foo2qpdl			      ldappasswd		   pod2man			      taskset			       zstdgrep
 foo2qpdl-wrapper		      ldapsearch		   pod2text			      tbl			       zstdless
 foo2slx			      ldapurl			   pod2usage			      tclsh			       zstdmt
 foo2slx-wrapper		      ldapwhoami		   podchecker			      tclsh8.6
 foo2xqx			      ld.bfd			   poff				      tcpdump
 foo2xqx-wrapper		      ldd			   pon				      tecla
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/bin$ ./ls
'['				      foo2zjs			   ld.gold			      POST			       tee
 aa-enabled			      foo2zjs-icc2ps		   ld.so			      powerprofilesctl		       telnet
 aa-exec			      foo2zjs-pstops		   less				      ppdc			       tempfile
 aa-features-abi		      foo2zjs-wrapper		   lessecho			      ppdhtml			       test
 aconnect			      foomatic-rip		   lessfile			      ppdi			       tic
 acpidbg			      fprintd-delete		   lesskey			      ppdmerge			       tificc
 add-apt-repository		      fprintd-enroll		   lesspipe			      ppdpo			       time
 addpart			      fprintd-list		   lexgrog			      pphs			       timedatectl
 addr2line			      fprintd-verify		   libnetcfg			      pr			       timeout
 airscan-discover		      free			   link				      precat			       tload
 alsabat			      ftp			   linkicc			      preconv			       tnftp
 alsaloop			      funzip			   linux32			      preunzip			       toe
 alsamixer			      fuser			   linux64			      prezip			       top
 alsatplg			      fusermount		   linux-boot-prober		      prezip-bin		       touch
 alsaucm			      fusermount3		   linux-check-removal		      prime-select		       tput
 amidi				      fwupdmgr			   linux-update-symlinks	      prime-supported		       tr
 amixer				      fwupdtool			   linux-version		      printafm			       trace-cmd
 apg				      gamemoded			   listres			      printenv			       tracepath
 apgbfm				      gamma4scanimage		   ln				      printer-profile		       tracker3
 aplay				      gapplication		   lnstat			      printf			       tracker3-daemon
 aplaymidi			      gatttool			   loadkeys			      prlimit			       tracker3-endpoint
 apport-bug			      gcalccmd			   loadunimap			      pro			       tracker3-export
 apport-cli			      gcore			   locale			      prove			       tracker3-extract
 apport-collect			      gcr-viewer		   locale-check			      prtstat			       tracker3-help
 apport-unpack			      gcr-viewer-gtk4		   localectl			      ps			       tracker3-import
 appres				      gdb			   localedef			      ps2ascii			       tracker3-index
 appstreamcli			      gdb-add-index		   logger			      ps2epsi			       tracker3-info
 apropos			      gdbtui			   login			      ps2pdf			       tracker3-reset
 apt				      gdbus			   loginctl			      ps2pdf12			       tracker3-search
 apt-add-repository		      gdk-pixbuf-csource	   logname			      ps2pdf13			       tracker3-sparql
 apt-cache			      gdk-pixbuf-pixdata	   look				      ps2pdf14			       tracker3-sql
 apt-cdrom			      gdk-pixbuf-thumbnailer	   lowntfs-3g			      ps2pdfwr			       tracker3-status
 apt-config			      gdm-config		   lp				      ps2ps			       tracker3-tag
 aptdcon			      gdmflexiserver		   lpoptions			      ps2ps2			       transicc
 apt-extracttemplates		      gdm-screenshot		   lpq				      ps2txt			       transset
 apt-ftparchive			      gencat			   lpr				      psfaddtable		       troff
 apt-get			      geqn			   lprm				      psfgettable		       true
 apt-key			      GET			   lpstat			      psfstriptable		       truncate
 apt-mark			      getconf			   ls				      psfxtable			       trust
 apt-sortpkgs			      getent			   lsattr			      psicc			       tset
 ar				      getfacl			   lsblk			      pslog			       tsort
 arch				      getkeycodes		   lsb_release			      pstree			       tty
 arecord			      getopt			   lscpu			      pstree.x11		       turbostat
 arecordmidi			      gettext			   lshw				      ptar			       tzselect
 arm2hpdl			      gettext.sh		   lsinitramfs			      ptardiff			       ua
 as				      ghostscript		   lsipc			      ptargrep			       ubuntu-advantage
 aseqdump			      ginstall-info		   lslocks			      ptx			       ubuntu-bug
 aseqnet			      gio			   lslogins			      pw-cat			       ubuntu-core-launcher
 aspell				      gio-querymodules		   lsmem			      pw-cli			       ubuntu-distro-info
 aspell-import			      gipddecode		   lsmod			      pw-config			       ubuntu-drivers
 atobm				      gjs			   lsns				      pwd			       ubuntu-report
 awk				      gjs-console		   lsof				      pw-dot			       ubuntu-security-status
 axfer				      gkbd-keyboard-display	   lspci			      pw-dsdplay		       ucf
 b2sum				      glib-compile-schemas	   lspgpot			      pw-dump			       ucfq
 baobab				      gnome-calculator		   lspower			      pwdx			       ucfr
 base32				      gnome-characters		   lsusb			      pw-encplay		       uclampset
 base64				      gnome-clocks		   lwp-download			      pw-link			       ucs2any
 basename			      gnome-control-center	   lwp-dump			      pw-loopback		       udevadm
 basenc				      gnome-disk-image-mounter	   lwp-mirror			      pw-metadata		       udisksctl
 bash				      gnome-disks		   lwp-request			      pw-mididump		       ul
 bashbug			      gnome-extensions		   lzcat			      pw-midiplay		       umax_pp
 bc				      gnome-font-viewer		   lzcmp			      pw-midirecord		       umount
 bdftopcf			      gnome-help		   lzdiff			      pw-mon			       uname
 bdftruncate			      gnome-keyring		   lzegrep			      pw-play			       unattended-upgrade
 bitmap				      gnome-keyring-3		   lzfgrep			      pw-profiler		       unattended-upgrades
 bluemoon			      gnome-keyring-daemon	   lzgrep			      pw-record			       uncompress
 bluetoothctl			      gnome-language-selector	   lzless			      pw-reserve		       unexpand
 bluetooth-sendto		      gnome-logs		   lzma				      pw-top			       unicode_start
 bmtoa				      gnome-power-statistics	   lzmainfo			      py3clean			       unicode_stop
 boltctl			      gnome-session		   lzmore			      py3compile		       uniq
 bpftrace			      gnome-session-inhibit	   m17n-db			      py3versions		       unity-scope-loader
 bpftrace-aotrt			      gnome-session-properties	   m2300w			      pybabel			       unlink
 brltty				      gnome-session-quit	   m2300w-wrapper		      pybabel-python3		       unlzma
 brltty-atb			      gnome-shell		   m2400w			      pydoc3			       unmkinitramfs
 brltty-clip			      gnome-shell-extension-tool   man				      pydoc3.12			       unshare
 brltty-ctb			      gnome-shell-test-tool	   mandb			      pygettext3		       unsquashfs
 brltty-hid			      gnome-system-monitor	   manpath			      pygettext3.12		       unxz
 brltty-ktb			      gnome-terminal		   man-recode			      pygmentize		       unzip
 brltty-lscmds			      gnome-terminal.real	   mapscrn			      pyserial-miniterm		       unzipsfx
 brltty-morse			      gnome-terminal.wrapper	   markdown-it			      pyserial-ports		       unzstd
 brltty-trtxt			      gnome-text-editor		   mawk				      python3			       update-alternatives
 brltty-ttb			      gnome-thumbnail-font	   mbimcli			      python3.12		       update-desktop-database
 brltty-tune			      gnome-www-browser		   mbim-network			      pzstd			       update-manager
 broadwayd			      gold			   mcookie			      qmicli			       update-mime-database
 browse				      gp-archive		   md5sum			      qmi-firmware-update	       update-notifier
 btattach			      gpasswd			   md5sum.textutils		      qmi-network		       upower
 btmgmt				      gp-collect-app		   mdig				      qpdldecode		       uptime
 btmon				      gp-display-html		   memhog			      quirks-handler		       usb-devices
 busctl				      gp-display-src		   memusage			      ranlib			       usbhid-dump
 busybox			      gp-display-text		   memusagestat			      rbash			       usbip
 bwrap				      gpg			   mesa-overlay-control.py	      rctest			       usbipd
 calibrate_ppa			      gpg-agent			   mesg				      rdma			       usb_printerid
 canberra-gtk-play		      gpgconf			   migratepages			      readelf			       usbreset
 cancel				      gpg-connect-agent		   migrate-pubring-from-classic-gpg   readlink			       users
 captoinfo			      gpgparsemail		   migspeed			      realpath			       utmpdump
 cat				      gpgsm			   mimeopen			      red			       uuidgen
 catman				      gpgsplit			   mimetype			      rename.ul			       uuidparse
 cd-create-profile		      gpgtar			   min12xxw			      rendercheck		       varlinkctl
 cd-fix-profile			      gpgv			   mkdir			      renice			       vcs-run
 cd-iccdump			      gpg-wks-client		   mkfifo			      reset			       vdir
 cd-it8				      gpic			   mkfontdir			      resizecons		       vi
 c++filt			      gprof			   mkfontscale			      resizepart		       view
 chacl				      gprofng			   mk_modmap			      resolvectl		       viewres
 chage				      gpu-manager		   mknod			      rev			       vim.tiny
 chardet			      grdctl			   mksquashfs			      rfcomm			       vmstat
 chardetect			      grep			   mktemp			      rgrep			       vmwarectrl
 chattr				      gresource			   mmcli			      rm			       vstp
 chcon				      groff			   mokutil			      rmdir			       w
 check-language-support		      grog			   monitor-sensor		      rnano			       wall
 chfn				      grops			   more				      routel			       watch
 chgrp				      grotty			   mount			      rpcgen			       watchgnupg
 chmod				      groups			   mountpoint			      rrsync			       wc
 choom				      growpart			   mousetweaks			      rstart			       wdctl
 chown				      grub-editenv		   mpris-proxy			      rstartd			       wget
 chrt				      grub-file			   mpstat			      rsync			       whatis
 chsh				      grub-fstest		   mscompress			      rsync-ssl			       whereis
 chvt				      grub-glue-efi		   msexpand			      rtla			       which
 cifsiostat			      grub-kbdcomp		   mt				      rtstat			       which.debianutils
 ciptool			      grub-menulst2cfg		   mt-gnu			      runcon			       whiptail
 ckbcomp			      grub-mkfont		   mtr				      run-parts			       who
 cksum				      grub-mkimage		   mtrace			      run-with-aspell		       whoami
 clear				      grub-mklayout		   mtr-packet			      rview			       whoopsie
 clear_console			      grub-mknetdir		   mv				      rygel			       whoopsie-preferences
 cloud-id			      grub-mkpasswd-pbkdf2	   namei			      sadf			       wireplumber
 cloud-init			      grub-mkrelpath		   nano				      sane-find-scanner		       word-list-compress
 cloud-init-per			      grub-mkrescue		   nautilus			      sar			       wpa_passphrase
 cmp				      grub-mkstandalone		   nautilus-autorun-software	      sar.sysstat		       wpctl
 codepage			      grub-mount		   nautilus-sendto		      savelog			       wpexec
 col				      grub-render-label		   nawk				      sbattach			       write
 colcrt				      grub-script-check		   nc				      sbkeysync			       X
 colormgr			      grub-syslinux2cfg		   nc.openbsd			      sbsiglist			       X11
 colrm				      gs			   neqn				      sbsign			       x11perf
 column				      gsbj			   netaddr			      sbvarsign			       x11perfcomp
 comm				      gsdj			   netcat			      sbverify			       x86_64
 corelist			      gsdj500			   networkctl			      scanimage			       x86_64-linux-gnu-addr2line
 cp				      gsettings			   networkd-dispatcher		      scp			       x86_64-linux-gnu-ar
 cpan				      gslj			   newgrp			      scp-dbus-service		       x86_64-linux-gnu-as
 cpan5.38-x86_64-linux-gnu	      gslp			   ngettext			      screendump		       x86_64-linux-gnu-c++filt
 cpio				      gsnd			   nice				      script			       x86_64-linux-gnu-cpp
 cpp				      gst-device-monitor-1.0	   nisdomainname		      scriptlive		       x86_64-linux-gnu-cpp-13
 cpp-13				      gst-discoverer-1.0	   nl				      scriptreplay		       x86_64-linux-gnu-dwp
 cpupower			      gst-inspect-1.0		   nm				      sdiff			       x86_64-linux-gnu-elfedit
 c_rehash			      gst-launch-1.0		   nm-applet			      sdptool			       x86_64-linux-gnu-gold
 crontab			      gst-play-1.0		   nmcli			      seahorse			       x86_64-linux-gnu-gp-archive
 csplit				      gstreamer-codec-install	   nm-connection-editor		      sed			       x86_64-linux-gnu-gp-collect-app
 ctstat				      gst-stats-1.0		   nm-online			      select-default-iwrap	       x86_64-linux-gnu-gp-display-html
 cupstestppd			      gst-tester-1.0		   nmtui			      select-editor		       x86_64-linux-gnu-gp-display-src
 cut				      gst-typefind-1.0		   nmtui-connect		      sensible-browser		       x86_64-linux-gnu-gp-display-text
 cvt				      gtbl			   nmtui-edit			      sensible-editor		       x86_64-linux-gnu-gprof
 cvtsudoers			      gted			   nmtui-hostname		      sensible-pager		       x86_64-linux-gnu-gprofng
 dash				      gtf			   nohup			      sensible-terminal		       x86_64-linux-gnu-ld
 date				      gtk4-broadwayd		   notify-send			      seq			       x86_64-linux-gnu-ld.bfd
 dbus-cleanup-sockets		      gtk4-builder-tool		   nproc			      session-migration		       x86_64-linux-gnu-ld.gold
 dbus-daemon			      gtk4-encode-symbolic-svg	   nroff			      sessreg			       x86_64-linux-gnu-nm
 dbus-monitor			      gtk4-launch		   nsenter			      setarch			       x86_64-linux-gnu-objcopy
 dbus-run-session		      gtk4-path-tool		   nslookup			      setfacl			       x86_64-linux-gnu-objdump
 dbus-send			      gtk4-query-settings	   nstat			      setfont			       x86_64-linux-gnu-pkgconf
 dbus-update-activation-environment   gtk4-rendernode-tool	   nsupdate			      setkeycodes		       x86_64-linux-gnu-pkg-config
 dbus-uuidgen			      gtk4-update-icon-cache	   ntfs-3g			      setleds			       x86_64-linux-gnu-ranlib
 dbxtool			      gtk-builder-tool		   ntfs-3g.probe		      setlogcons		       x86_64-linux-gnu-readelf
 dc				      gtk-encode-symbolic-svg	   ntfscat			      setmetamode		       x86_64-linux-gnu-size
 dconf				      gtk-launch		   ntfscluster			      setpci			       x86_64-linux-gnu-strings
 dd				      gtk-query-settings	   ntfscmp			      setpriv			       x86_64-linux-gnu-strip
 ddstdecode			      gtk-update-icon-cache	   ntfsdecrypt			      setsid			       x86_energy_perf_policy
 deallocvt			      gunzip			   ntfsfallocate		      setterm			       xargs
 debconf			      gzexe			   ntfsfix			      setupcon			       xauth
 debconf-apt-progress		      gzip			   ntfsinfo			      setxkbmap			       xbiff
 debconf-communicate		      h2ph			   ntfsls			      sftp			       xbrlapi
 debconf-copydb			      h2xs			   ntfsmove			      sg			       xcalc
 debconf-escape			      hardlink			   ntfsrecover			      sh			       xclipboard
 debconf-set-selections		      hbpldecode		   ntfssecaudit			      sha1sum			       xclock
 debconf-show			      hciattach			   ntfstruncate			      sha224sum			       xcmsdb
 debian-distro-info		      hciconfig			   ntfsusermap			      sha256sum			       xconsole
 deb-systemd-helper		      hcitool			   ntfswipe			      sha384sum			       xcursorgen
 deb-systemd-invoke		      hd			   numactl			      sha512sum			       xcutsel
 delpart			      head			   numastat			      shasum			       xdg-dbus-proxy
 delv				      HEAD			   numfmt			      showconsolefont		       xdg-desktop-icon
 desktop-file-edit		      heif-thumbnailer		   nvidia-bug-report.sh		      showkey			       xdg-desktop-menu
 desktop-file-install		      helpztags			   nvidia-cuda-mps-control	      showrgb			       xdg-email
 desktop-file-validate		      hex2hcd			   nvidia-cuda-mps-server	      shred			       xdg-icon-resource
 df				      hexdump			   nvidia-debugdump		      shuf			       xdg-mime
 dh_bash-completion		      hipercdecode		   nvidia-detector		      size			       xdg-open
 dh_installxmlcatalogs		      host			   nvidia-ngx-updater		      skill			       xdg-screensaver
 dh_perl_openssl		      hostid			   nvidia-persistenced		      slabtop			       xdg-settings
 diff				      hostname			   nvidia-powerd		      sleep			       xdg-user-dir
 diff3				      hostnamectl		   nvidia-settings		      slogin			       xdg-user-dirs-gtk-update
 dig				      hp-align			   nvidia-sleep.sh		      slxdecode			       xdg-user-dirs-update
 dir				      hp-check			   nvidia-smi			      smproxy			       xditview
 dircolors			      hp-clean			   nvidia-xconfig		      snap			       xdpyinfo
 dirmngr			      hp-colorcal		   oakdecode			      snapctl			       xdriinfo
 dirmngr-client			      hp-config_usb_printer	   obexctl			      snapfuse			       xedit
 dirname			      hp-doctor			   objcopy			      snice			       Xephyr
 distro-info			      hp-firmware		   objdump			      soelim			       xev
 dmesg				      hp-info			   oclock			      software-properties-gtk	       xeyes
 dnsdomainname			      hp-levels			   od				      sort			       xfd
 domainname			      hp-logcapture		   oem-getlogs			      sotruss			       xfontsel
 do-release-upgrade		      hp-makeuri		   on_ac_power			      spa-acp-tool		       xgamma
 dpkg				      hp-pkservice		   oomctl			      spa-inspect		       xgc
 dpkg-deb			      hp-plugin			   open				      spa-json-dump		       xhost
 dpkg-divert			      hp-plugin-ubuntu		   openssl			      spa-monitor		       xinit
 dpkg-maintscript-helper	      hp-probe			   openvt			      spa-resample		       xinput
 dpkg-query			      hp-query			   opldecode			      spd-conf			       xkbbell
 dpkg-realpath			      hp-scan			   orca				      spd-say			       xkbcomp
 dpkg-split			      hp-setup			   orca-dm-wrapper		      spdsend			       xkbevd
 dpkg-statoverride		      hp-testpage		   os-prober			      speaker-test		       xkbprint
 dpkg-trigger			      hp-timedate		   p11-kit			      speech-dispatcher		       xkbvleds
 driverless			      hwe-support-status	   pager			      spice-vdagent		       xkbwatch
 driverless-fax			      i386			   paperconf			      splain			       xkeystone
 du				      ibus			   partx			      split			       xkill
 dumpkeys			      ibus-daemon		   passwd			      splitfont			       xload
 dvipdf				      ibus-setup		   paste			      sprof			       xlogo
 dwp				      ibus-table-createdb	   patch			      sqfscat			       xlsatoms
 eatmydata			      iceauth			   pathchk			      sqfstar			       xlsclients
 ec2metadata			      ico			   pdb3				      ss			       xlsfonts
 echo				      iconv			   pdb3.12			      ssh			       xmag
 ed				      id			   pdf2dsc			      ssh-add			       xman
 editor				      iecset			   pdf2ps			      ssh-agent			       xmessage
 editres			      ijs_pxljr			   pdfattach			      ssh-argv0			       xmodmap
 efibootdump			      im-config			   pdfdetach			      ssh-copy-id		       xmore
 efibootmgr			      im-launch			   pdffonts			      ssh-keygen		       Xorg
 egrep				      inetutils-telnet		   pdfimages			      ssh-keyscan		       xprop
 eject				      info			   pdfinfo			      sss_ssh_authorizedkeys	       xqxdecode
 elfedit			      infobrowser		   pdfseparate			      sss_ssh_knownhostsproxy	       xrandr
 enc2xs				      infocmp			   pdfsig			      startx			       xrdb
 encguess			      infotocap			   pdftocairo			      stat			       xrefresh
 enchant-2			      inputattach		   pdftohtml			      static-sh			       x-session-manager
 enchant-lsmod-2		      install			   pdftoppm			      stdbuf			       xset
 env				      install-info		   pdftops			      strace			       xsetmode
 envsubst			      instmodsh			   pdftotext			      strace-log-merge		       xsetpointer
 eog				      intel-virtual-output	   pdfunite			      streamzip			       xsetroot
 eps2eps			      ionice			   peekfd			      strings			       xsetwacom
 eqn				      iostat			   perf				      strip			       xsm
 esc-m				      ip			   perl				      stty			       xstdcmap
 eutp				      ipcmk			   perl5.38.2			      su			       xsubpp
 evince				      ipcrm			   perl5.38-x86_64-linux-gnu	      sudo			       x-terminal-emulator
 evince-previewer		      ipcs			   perlbug			      sudoedit			       xvidtune
 evince-thumbnailer		      ippfind			   perldoc			      sudoreplay		       xvinfo
 ex				      ipptool			   perli11ndoc			      sum			       Xwayland
 expand				      iptables-xml		   perlivp			      switcherooctl		       xwd
 expiry				      ischroot			   perlthanks			      sync			       xwininfo
 expr				      isdv4-serial-debugger	   pf2afm			      systemctl			       xwud
 factor				      isdv4-serial-inputattach	   pfbtopfa			      systemd			       x-www-browser
 faillog			      ispell-wrapper		   pgrep			      systemd-ac-power		       xxd
 fallocate			      join			   pic				      systemd-analyze		       xz
 false				      journalctl		   pico				      systemd-ask-password	       xzcat
 fc-cache			      jpgicc			   piconv			      systemd-cat		       xzcmp
 fc-cat				      jq			   pidof			      systemd-cgls		       xzdiff
 fc-conflist			      jsondiff			   pidstat			      systemd-cgtop		       xzegrep
 fc-list			      jsonpatch			   pidwait			      systemd-confext		       xzfgrep
 fc-match			      json-patch-jsondiff	   pinentry			      systemd-creds		       xzgrep
 fc-pattern			      jsonpointer		   pinentry-curses		      systemd-cryptenroll	       xzless
 fc-query			      json_pp			   pinentry-gnome3		      systemd-cryptsetup	       xzmore
 fc-scan			      jsonschema		   pinentry-x11			      systemd-delta		       yelp
 fc-validate			      kbdinfo			   ping				      systemd-detect-virt	       yes
 fgconsole			      kbd_mode			   ping4			      systemd-escape		       ypdomainname
 fgrep				      kbxutil			   ping6			      systemd-firstboot		       zcat
 file				      kernel-install		   pinky			      systemd-hwdb		       zcmp
 file2brl			      kerneloops-submit		   pipewire			      systemd-id128		       zdiff
 find				      kill			   pipewire-aes67		      systemd-inhibit		       zdump
 findmnt			      killall			   pipewire-avb			      systemd-machine-id-setup	       zegrep
 firefox			      kmod			   pipewire-pulse		      systemd-mount		       zenity
 flock				      kmodsign			   pkaction			      systemd-notify		       zfgrep
 fmt				      l2ping			   pkcheck			      systemd-path		       zforce
 fold				      l2test			   pkcon			      systemd-repart		       zgrep
 fonttosfnt			      laptop-detect		   pkexec			      systemd-run		       zip
 foo2ddst			      last			   pkgconf			      systemd-socket-activate	       zipcloak
 foo2ddst-wrapper		      lastb			   pkg-config			      systemd-stdio-bridge	       zipdetails
 foo2hbpl2			      lastlog			   pkill			      systemd-sysext		       zipgrep
 foo2hbpl2-wrapper		      lavadecode		   pkmon			      systemd-sysusers		       zipinfo
 foo2hiperc			      lcf			   pkttyagent			      systemd-tmpfiles		       zipnote
 foo2hiperc-wrapper		      ld			   pl2pm			      systemd-tty-ask-password-agent   zipsplit
 foo2hp				      ldapadd			   pldd				      systemd-umount		       zjsdecode
 foo2hp2600-wrapper		      ldapcompare		   plog				      tabs			       zless
 foo2lava			      ldapdelete		   plymouth			      tac			       zmore
 foo2lava-wrapper		      ldapexop			   pmap				      tail			       znew
 foo2oak			      ldapmodify		   pnm2ppa			      tapestat			       zstd
 foo2oak-wrapper		      ldapmodrdn		   pod2html			      tar			       zstdcat
 foo2qpdl			      ldappasswd		   pod2man			      taskset			       zstdgrep
 foo2qpdl-wrapper		      ldapsearch		   pod2text			      tbl			       zstdless
 foo2slx			      ldapurl			   pod2usage			      tclsh			       zstdmt
 foo2slx-wrapper		      ldapwhoami		   podchecker			      tclsh8.6
 foo2xqx			      ld.bfd			   poff				      tcpdump
 foo2xqx-wrapper		      ldd			   pon				      tecla
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/bin$ ls | grep
Usage: grep [OPTION]... PATTERNS [FILE]...
Try 'grep --help' for more information.
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/bin$ ls | grep ls
alsabat
alsaloop
alsamixer
alsatplg
alsaucm
brltty-lscmds
enchant-lsmod-2
false
grub-menulst2cfg
hp-levels
inetutils-telnet
ls
lsattr
lsblk
lsb_release
lscpu
lshw
lsinitramfs
lsipc
lslocks
lslogins
lsmem
lsmod
lsns
lsof
lspci
lspgpot
lspower
lsusb
md5sum.textutils
ntfsls
pipewire-pulse
systemd-cgls
tclsh
tclsh8.6
which.debianutils
xlsatoms
xlsclients
xlsfonts
zipdetails
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/bin$ cd ..
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/$ ls
bin		   boot   dev  home  lib64		lost+found  mnt  proc  run   sbin.usr-is-merged  srv	   sys	usr
bin.usr-is-merged  cdrom  etc  lib   lib.usr-is-merged	media	    opt  root  sbin  snap		 swap.img  tmp	var
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/$ cd opt
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/opt$ ls
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:/opt$ cd ~
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ cd 
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ cd //
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx://$ cd ~
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ mkdir traningMia
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ cd traningMia/
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ touch test7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ nano test7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ ls
test7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ ./test7.2
bash: ./test7.2: Permission denied
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ ls -l
total 4
-rw-rw-r-- 1 areej-maher areej-maher 71 Aug 10 21:24 test7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ ./test7.2
bash: ./test7.2: Permission denied
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ chmod +x test7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ ls -l
total 4
-rwxrwxr-x 1 areej-maher areej-maher 71 Aug 10 21:24 test7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ chmod g=r test7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ ./test7.2
folder1  test7.2
folder1  folder2  test7.2
folder1  folder2  HEllO.txt  test7.2
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~/traningMia$ cd ~
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls -a
.   .bash_history  .bashrc  .config  Documents	-l	  .local  Music     .profile  snap  Templates	Videos
..  .bash_logout   .cache   Desktop  Downloads	.lesshst  mia7.2  Pictures  Public    .ssh  traningMia
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ ls -al
total 100
drwxr-x--- 17 areej-maher areej-maher 4096 Aug 10 21:22 .
drwxr-xr-x  3 root        root        4096 Aug 10 20:28 ..
-rw-------  1 areej-maher areej-maher  603 Aug 10 21:01 .bash_history
-rw-r--r--  1 areej-maher areej-maher  220 Mar 31 10:41 .bash_logout
-rw-r--r--  1 areej-maher areej-maher 3788 Aug 10 20:59 .bashrc
drwx------ 10 areej-maher areej-maher 4096 Aug 10 20:31 .cache
drwx------ 11 areej-maher areej-maher 4096 Aug 10 21:03 .config
drwxr-xr-x  3 areej-maher areej-maher 4096 Aug 10 21:11 Desktop
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Documents
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Downloads
-rw-r--r--  1 areej-maher areej-maher 9546 Aug 10 21:18 -l
-rw-------  1 areej-maher areej-maher   20 Aug 10 21:18 .lesshst
drwx------  4 areej-maher areej-maher 4096 Aug 10 20:29 .local
drwxrwxr-x  4 areej-maher areej-maher 4096 Aug 10 20:57 mia7.2
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Music
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Pictures
-rw-r--r--  1 areej-maher areej-maher  807 Mar 31 10:41 .profile
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Public
drwx------  4 areej-maher areej-maher 4096 Aug 10 21:00 snap
drwx------  2 areej-maher areej-maher 4096 Aug 10 20:29 .ssh
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Templates
drwxrwxr-x  4 areej-maher areej-maher 4096 Aug 10 21:25 traningMia
drwxr-xr-x  2 areej-maher areej-maher 4096 Aug 10 20:29 Videos
areej-maher@areej-maher-HP-Pavilion-Gaming-Laptop-15-dk1xxx:~$ nano .bashrc


