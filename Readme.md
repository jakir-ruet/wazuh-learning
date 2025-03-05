## More About Me – [Take a Look!](http://www.mjakaria.me) 

### What is Wazuh? 
Wazuh is an open-source security monitoring platform that provides log analysis, intrusion detection, vulnerability detection, and compliance monitoring. It can monitor your infrastructure for suspicious activity, configuration changes, and more.

### Install on Docker
```bash
sysctl -w vm.max_map_count=262144 # Increase max_map_count on your Docker host
```
```bash
curl -sSL https://get.docker.com/ | sh # Docker installation script
```
```bash
systemctl start docker # Start Docker
```
**Download the Docker Compose binary**
```bash
curl -L "https://github.com/docker/compose/releases/download/v2.12.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose # Grant execution permissions
docker-compose --version
```

**Wazuh Docker deployment** You can deploy Wazuh as a single-node or multi-node stack.
- Single-node deployment: Deploys one Wazuh manager, indexer, and dashboard node.
- Multi-node deployment: Deploys two Wazuh manager nodes (one master and one worker), three Wazuh indexer nodes, and a Wazuh dashboard node.
I've installed it here as a `Single Node`.
```bash
git clone https://github.com/wazuh/wazuh-docker.git -b v4.11.0
```

## With Regards, `Jakir`

[![LinkedIn][linkedin-shield-jakir]][linkedin-url-jakir]
[![Facebook-Page][facebook-shield-jakir]][facebook-url-jakir]
[![Youtube][youtube-shield-jakir]][youtube-url-jakir]

### Wishing you a wonderful day! Keep in touch.

<!-- Personal profile -->

[linkedin-shield-jakir]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-jakir]: https://www.linkedin.com/in/jakir-ruet/
[facebook-shield-jakir]: https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white
[facebook-url-jakir]: https://www.facebook.com/jakir.ruet/
[youtube-shield-jakir]: https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white
[youtube-url-jakir]: https://www.youtube.com/@mjakaria-ruet/featured
