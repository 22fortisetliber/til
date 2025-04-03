# Resize Disk

```
# sudo apt install parted -y
```

## Check disk and partitions
```
# lsblk
```

## Resize Disk
```
# parted

(parted) print
(parted) resizepart <partition number>
```

## Check disk and partitions after resize
```
# lsblk
```

## Update partition
```
resize2fs /dev/sda5 
```
