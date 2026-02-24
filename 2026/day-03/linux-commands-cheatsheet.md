*Linux Command Cheat Sheet*

A quick reference for real-world troubleshooting and DevOps tasks.

*File System Commands*

Command	Usage
pwd	Show current working directory
ls -la	List all files (including hidden) with details
cd <dir>	Change directory
mkdir <dir>	Create a new directory
rmdir <dir>	Remove empty directory
rm -rf <dir>	Remove directory recursively
cp -r src dest	Copy files/directories
mv src dest	Move or rename files
touch file.txt	Create empty file
find . -name "file.txt"	Search for file
du -sh *	Show size of folders
df -h	Show disk space usage

*Process Management Commands*

Command	Usage
ps aux	Show all running processes
top	Real-time process monitor
htop	Advanced interactive process viewer
kill <PID>	Terminate process by PID
kill -9 <PID>	Force kill process
pkill <name>	Kill process by name
jobs	Show background jobs
bg	Resume job in background
fg	Bring job to foreground
uptime	Show system uptime and load average
free -h	Show memory usage

*Networking & Troubleshooting Commands*

Command	Usage
ping google.com	Check network connectivity
ip addr	Show IP addresses
curl -I https://example.com	Check HTTP response headers
netstat -tulnp	Show open and listening ports
ss -tuln	Display active listening ports
dig google.com	DNS lookup
traceroute google.com	Trace route to host

*Logs & Permissions (Very Important for DevOps*)
Command	Usage
tail -f /var/log/syslog	Monitor logs in real-time
head file.log	Show first 10 lines
less file.log	Scroll through large file
cat file.log	Display entire file
grep "error" file.log	Search inside file
chmod 755 file	Change file permissions
chown user:group file	Change file ownership
