# Monitoring Tools

- `iostat`: Report Central Processing Unit (CPU) statistics and input/output statistics for devices and partitions. It can be used to report the disk read/write rates and counts for an interval continuously. It collects disk statistics, waits for the given amount of time, collects them again and displays the difference.

  - http://manpages.ubuntu.com/manpages/bionic/man1/iostat.1.html

- `iotop`: Simple top-like I/O monitor. It is a top-like utility for displaying real-time disk activity. It can list the processes that are performing I/O, alongwith the disk bandwidth they are using

  - http://manpages.ubuntu.com/manpages/bionic/man8/iotop.8.html

- `dstat`: Versatile resource statistics tool. It is a little more user-friendly version of `iostat`, and can show much more information than just disk bandwidth

  - http://dag.wiee.rs/home-made/dstat/

- `atop`: Atop is an ASCII full-screen performance monitor for Linux that is capable of reporting the activity of all processes (even if processes have finished during the interval), daily logging of system and process activity for long-term analysis, highlighting overloaded system resources by using colors, etc. At regular intervals, it shows system-level activity related to the CPU, memory, swap, disks (including LVM) and network layers, and for every process (and thread) it shows e.g. the CPU utilization, memory growth, disk utilization, priority, username, state, and exit code.
  In combination with the *optional* kernel module [netatop](https://www.atoptool.nl/netatop.php), it even shows network activity per process/thread.

  - https://www.atoptool.nl/index.php

- `ioping`: Simple disk I/O latency monitoring tool. It is a quick and dirty storage volume latency checker. It is useful for checking if the elevated disk times that you’re seeing are because of a degradation of the underlying virtual disk / network / hardware.

  - http://manpages.ubuntu.com/manpages/bionic/man1/ioping.1.html


