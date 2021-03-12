[ERROR]
max virtual memory areas vm.max_map_count [65530] is too low, increase to at least [262144]

[FIX]
open powershell<br>
wsl -d docker-desktop<br>
sysctl -w vm.max_map_count=262144<br>
<br>
restart Docker 
