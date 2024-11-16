# Docker Installation Guide for Debian

**Download the installation script from source**
```
curl -fsSL https://get.docker.com -o get-docker.sh
```

<br>

**Execute the installation script as sudo**
```
sudo sh ./get-docker.sh
```

<br>

**Allow docker daemon to run without sudo**
```
sudo groupadd docker
```

```
sudo usermod -aG docker $USER
```

```
newgrp docker
```
