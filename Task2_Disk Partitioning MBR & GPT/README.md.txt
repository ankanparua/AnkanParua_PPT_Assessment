# Disk Partitioning: MBR & GPT

## Project Overview
This project demonstrates disk partitioning on Ubuntu (using MBR) and Windows (using GPT). It teaches the fundamentals of storage structures and disk management.

## Objective
- Create and manage disk partitions on Linux and Windows.
- Understand differences between MBR and GPT partitioning schemes.

## Steps

### Ubuntu (MBR)
1. Open terminal and list disks:
   ```bash
   sudo fdisk -l
   sudo fdisk /dev/sdX