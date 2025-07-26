Operating-System-Mini-Project
This Linux Kernel Module (LKM) project demonstrates hierarchical thread creation and process management in the Linux kernel. The root process creates three threads, each of which recursively spawns three more, forming a three-level process tree. For every thread created, the module prints a tree-structured output showing the task name, PID and whether the PID is even or odd.

The output uses indentation to reflect the hierarchy and showcases parent-child and sibling relationships clearly. This project highlights key OS concepts such as kernel threading, task_struct traversal offering hands-on experience with Linux kernel internals and concurrency.
