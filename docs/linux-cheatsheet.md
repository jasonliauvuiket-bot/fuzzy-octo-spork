# Linux Command Cheatsheet

## Navigation
- pwd — print current directory
- ls -l — detailed listing
- cd <dir> — change directory
- cd .. — go up one level

## File Operations
- cp <src> <dst> — copy file
- mv <src> <dst> — rename/move file
- rm <file> — delete file
- rm -r <dir> — delete directory recursively
- mkdir <dir> — create directory

## Content Inspection
- cat <file> — print content
- less <file> — view with pagination
- head <file> — first 10 lines
- tail <file> — last 10 lines
- tail -f <file> — live log view

## Search
- grep "<pattern>" <file>
- grep -r "<pattern>" <dir>
- find <path> -name "<filename>"

## System Info
- top — process monitor
- df -h — disk usage
- free -h — memory usage
- uptime — load summary

## Networking
- ip a — network interfaces
- ping <host>
- traceroute <host>
- ss -tulpn — ports in use

## Processes
- ps aux — list processes
- kill <pid>
- kill -9 <pid> — force kill
- systemctl status <service>

## Compression
- tar -czvf x.tar.gz <folder>
- tar -xzvf x.tar.gz
- unzip x.zip

## Permissions
- chmod 755 <file>
- chown user:group <file>
- sudo <cmd>
