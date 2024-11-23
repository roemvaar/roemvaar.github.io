---
layout: post
title: "ELC: Linux in Space (thoughts)"
date: 2024-10-31 00:32:13
description: My thoughts on the Linux in Space from the Europe 2024 Embedded Linux Conference.
tags: rtos
categories: OSo
tabs: true
---

I've watched the "*Linux in Space: Fault detection, recovery and fault-tolerant system designs*" and here are my thoughts.

You can find the video and slides [here](https://osseu2024.sched.com/event/1ej1t/linux-in-space-fault-detection-recovery-and-fault-tolerant-system-designs-lenka-koskova-triskova-lukas-mazl-technical-university-of-liberec-tomas-novotny-vzlu).

## Fault Tolerant Design Principles

Design for spacecraft is a bit more complicated.
The specific challenges presented in the environment are due
to radiation, extreme temperatures, and no physical access.

Fault tolerance is the syste's ability to overcome and handle
failures.

Fault Detection, Isolation, and Recovery (FDIR) is a field
that concers with monitoring a system, identifying when a fault
has ocurred, and pinpoiting the type of fault and its location.

Redundancy designs are used in space technology.

## System updates

Over the Air updates.

## System

Duplicate critical system images as bootloader, kernel, and
rootfs.

They build the system using Yocto.

Das U-Boot as the bootloader.
