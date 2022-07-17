# Linux

History on Unix
The OS wars

neofetch

```
uname -a
cat /etc/os-release
```


## Distributions
interested in 

Ubuntu 

Fedora / red hat

red hat education program

Arch

elementaryOS

SELinux

Desktop enviroment
Gnmone
KDE
deepin
patheon 
buggie

wine
lutris
opendestop org
container

system adminstrator

## Shell 
commands options and arguments 
man pages

brackets optional
vertical bar (pipe) means only one of the options can be used at the time
``` 
    crontab [ -u user ] file
    crontab [ -u user ] [ -i ] { -e | -l | -r }
```


kernel space
user space

processes id

user proccess
deamon processes
kernel threats

```
    ps
```

## files 
directories

files

```
    cd ~
    mkdir playGround
    file playGround
    cd playGround
    cp /etc/fstab . # with the same name
```

links 
hard [default] 
soft 

```
    cd ~/playGround
    ln fstab hard_link
    ln -s fstab soft_link
    
    ls -l
```

block files

```
    file [file name]
```


## Filesystem Hierarchy Standar (FHS)
guidelines on how to organize the system's files
```
    cd /
    ls -l
```
 

bin: binary folder

```
   ls usr/sbin/ip

    ls sbin/ip
    
    whereis firefox
```

boot: where the kernel is 

grub2: bootloader

etc: configuration files

dev: devices files useful to interface with hardware
var: 


~/.local: 

aliases

shell documentation

```
    sudo apt install bash-doc
```

/usr/share/doc/bash/examples/startup-files

Linuxdoc) SGML


man 
apropos
info
whatis

man man-pages

development tolos for building source files


mantainable desing pattern
tools used by developer companies
bootstrap
database
CRUD

security autentification authorisation auth0
enterprise solve bussiness problem
bugzila

ticket tracket database

software requirements specification (SRS)
.NET ASP.NET
C#
Model–view–controller (usually known as MVC) 

elastic search

build tools

XAML

shine app
and r package

## package manager 
apt 

snap 

yummi


# tools to check computer info

check USB devices connected
```
lsusb 
    # Bus 002 Device 001: ID 1d6b:0003 Linux Foundation 3.0 root hubP
    # ....
    # Bus 001 Device 007: ID 0a12:0001 Cambridge Silicon Radio, Ltd Bluetooth Dongle (HCI mode)
lsusb -v -s 001:007
```

check bluetooth estatus with ```hcitool``` HCI (Host Control Interface) or the service and ```gatttool``` for BLE  (Bluetooth Low Energy) 

```
hcitool dev
sudo hciconfig -a hci0
sudo hcitool lescan
sudo service bluetooth status
```

bluetooth agent
```
bluetoothctl
```

parrot bluetooth adress
90:3A:E6:24:29:FE 
D0:3A:29:FE:E6:24
LE-reserved_k


## red hat free courses

https://www.redhat.com/rhtapps/promo-rh024/?segment=3

https://www.redhat.com/rhtapps/promo-rh018/?segment=0  


## Resources
[linux System Administrator's Guide](http://www.tldp.org/LDP/sag/html/index.html)

[Linux Network Administrators Guide](http://www.tldp.org/LDP/nag2/index.html)

[tldp guides](http://www.tldp.org/guides.html)
[The linux command line by William E. Shotts, Jr](http://www.linuxzasve.com/preuzimanje/TLCL-09.12.pdf)