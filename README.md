
Keterangan
==========

Install Docker Menggunakan Makefile
-----------
```bash
cd dockerinstallation
sudo make run
```

Install Docker Compose
-----------
```bash
sudo curl -L https://github.com/docker/compose/releases/download/1.18.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

Install Docker Portainer
-----------
```bash 
docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer
```
