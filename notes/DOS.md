# MS DOS OS

FreeDOS as Free software DOS replacement in new era.


Using FreeDOS to learn OS in Depth
```
$ sudo apt install qemu-system-i386
$ md5sum -c verify.txt --ignore-missing
$ unzip FD13-LiveCD.zip FD13LIVE.iso
$ qemu-img create -f qcow2 freedos.qcow2 500m
```

## Install FreeDOS on HDD
```
qemu-system-i386 -enable-kvm -m 32 -hda freedos.qcow2 -cdrom FD13LIVE.iso
```

# Run
```
qemu-system-i386 -enable-kvm -m 32 -hda freedos.qcow2
```

# Commands
```
help
ver
dir
cd 
time 
date
```

# TODO
Run doom
enable sound
work on serial port


---

# Resource

[1](https://www.both.org/?p=5612)

