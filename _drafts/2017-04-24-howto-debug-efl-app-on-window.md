On Windows host:
```
PS> .\gdbserver.exe --multi ip:2345 .\eflete.exe
```

Copy or make symlink to libraries
On Linux client:
```
$mkdir -p /tmp/sroot/C:/Users/rimmed/Desktop/windows_64/
$cd /tmp/sroot/C:/Users/rimmed/Desktop/windows_64/
$ln -s /opt/windows_64/bin/
$ln -s /opt/windows_64/lib

$gdb eflete.exe
gdb$ set target-file-system-kind dos-based
gdb$ target extended-remote ip:2345
gdb$ set sysroot /tmp/sroot/
```
