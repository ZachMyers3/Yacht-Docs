# ARM

## Memory support in graphs
If you're on arm and graphs aren't showing up add the following to your cmdline.txt:

!!! code "Arm RAM Fix"

        ```
        cgroup_enable=cpuset cgroup_enable=memory cgroup_memory=1
        ```