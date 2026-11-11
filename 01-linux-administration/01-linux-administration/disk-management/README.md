
# Linux Disk Management and Reporting

## Overview
Practical Linux storage management and
disk utilization reporting exercises.

## Objectives
- Identify block devices and partitions.
- Check filesystem utilization.
- Analyze directory sizes.
- Identify large directories.
- Generate a disk usage report.

## Commands Used

### List block devices
lsblk

### Check filesystem usage
df -h

### Analyze directory sizes
du -h --max-depth=1 /var

### Sort directory sizes
du -h --max-depth=1 /var | sort -rh

## Learning Outcome
Understand Linux storage utilization and
generate reports for system administration.
