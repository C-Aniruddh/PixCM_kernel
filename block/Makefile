#
# Makefile for the kernel block layer
#

obj-$(CONFIG_BLOCK) := elevator.o blk-core.o blk-tag.o blk-sysfs.o \
			blk-flush.o blk-settings.o blk-ioc.o blk-map.o \
			blk-exec.o blk-merge.o blk-softirq.o blk-timeout.o \
			blk-iopoll.o blk-lib.o ioctl.o genhd.o scsi_ioctl.o \
			partition-generic.o partitions/

obj-$(CONFIG_BLK_DEV_BSG)	+= bsg.o
obj-$(CONFIG_BLK_DEV_BSGLIB)	+= bsg-lib.o
obj-$(CONFIG_BLK_CGROUP)	+= blk-cgroup.o
obj-$(CONFIG_BLK_DEV_THROTTLING)	+= blk-throttle.o
obj-$(CONFIG_IOSCHED_NOOP)	+= noop-iosched.o
obj-$(CONFIG_IOSCHED_DEADLINE)	+= deadline-iosched.o
obj-$(CONFIG_IOSCHED_ROW)	+= row-iosched.o
obj-$(CONFIG_IOSCHED_CFQ)	+= cfq-iosched.o
<<<<<<< HEAD
obj-$(CONFIG_IOSCHED_BFQ)	+= bfq-iosched.o
=======
obj-$(CONFIG_IOSCHED_SIO)       += sio-iosched.o
<<<<<<< HEAD
>>>>>>> 9e7b925... Added SIO I/O Scheduler
obj-$(CONFIG_IOSCHED_TEST)	+= test-iosched.o
=======
obj-$(CONFIG_IOSCHED_FIOPS)     += fiops-iosched.o
<<<<<<< HEAD
>>>>>>> 4e3ec16... Added FIOPS I/O Scheduler
=======
obj-$(CONFIG_IOSCHED_VR)	+= vr-iosched.o
<<<<<<< HEAD
>>>>>>> 8b1c4f6... Added V(R) I/O Scheduler
=======
obj-$(CONFIG_IOSCHED_ZEN)	+= zen-iosched.o
<<<<<<< HEAD
>>>>>>> 5e90e2b... Added Zen IO scheduler
=======
obj-$(CONFIG_IOSCHED_ROW)	+= row-iosched.o
<<<<<<< HEAD
>>>>>>> b84c51b... Added ROW (Read Over Write) I/O scheduler
=======
obj-$(CONFIG_IOSCHED_SIOPLUS)   += sioplus-iosched.o
>>>>>>> d301bc1... Added Simple IO scheduler plus

obj-$(CONFIG_BLOCK_COMPAT)	+= compat_ioctl.o
obj-$(CONFIG_BLK_DEV_INTEGRITY)	+= blk-integrity.o
