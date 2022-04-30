IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.5.0
 
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0
 
PROJECT_NAME = LED_test
PROJECT_PATH := ../../LED_test/LED_test.tsproj
PLC = LED_test
 
PYTMC_OPTS :=
PREFIX = PLC:LED:TST
 
include $(IOC_TOP)/iocBoot/templates/Makefile.base

