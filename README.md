Install Guide (Linux):

Install any HTTP Proxy Software first and make sure it works wget https://github.com/lfasmpao/open-http-puncher/releases/download/0.1/ohpserver-linux32.zip unzip ohpserver-linux32.zip chmod +x ohpserver

Run server (Linux) screen -dm bash -c "./ohpserver.exe -port (server port) -proxy (HTTP proxy ip:port) -tunnel (redirection tunnel ip:port)" Run server (Windows): Open CMD and cd to the directory ohpserver.exe -port (server port) -proxy (HTTP proxy ip:port) -tunnel (redirection tunnel ip:port)

Sample Server Usage: Windows: SSH ohpserver.exe -port 5555 -proxy 127.0.0.1:3128 -tunnel 127.0.0.1:22

OpenVPN ohpserver.exe -port 5555 -proxy 127.0.0.1:3128 -tunnel 127.0.0.1:1194

Linux: SSH ./ohpserver -port 5555 -proxy 127.0.0.1:3128 -tunnel 127.0.0.1:22

OpenVPN ./ohpserver -port 5555 -proxy 127.0.0.1:3128 -tunnel 127.0.0.1:1194
