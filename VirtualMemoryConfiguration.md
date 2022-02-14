Out of memory (OOM) killer troubleshooting/configuration<br>
-----------------<br>
<br>
Config file -- /etc/sysctl.conf <br>
<br>
<br>
Values to experiment with:<br>
__<br>

vm.oom_kill_allocating_task<br>

vm.overcommit_memory = 2<br>
vm.overcommit_ratio = 80<br>
<br>
<br>
echo 2 > /proc/sys/vm/overcommit_memory
echo 80 > /proc/sys/vm/overcommit_ratio<br>
<br>
