# docker_vocbench3

Docker images for vocbench3 and a separate rdf4j (sesame) repository.

* http://vocbench.uniroma2.it/
* http://rdf4j.org/

Our implementation is hosted in a cloud machine on Ubuntu 18.04 LTS

To build with docker:

1. INstall docker using docker repostiory

```
sudo apt-get update
sudo apt-get install \
apt-transport-https \
ca-certificates \
curl \
gnupg-agent \
software-properties-common
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -


$ sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
$ sudo apt-get update
$ sudo apt-get install docker-ce docker-ce-cli containerd.io
$ sudo docker run hello-world
```
2. Install docker-compose
```

```

3. CLone repository
```
git clone https://github.com/internetofwater/docker-vocbench3.git
```

4. Compose docker image


```
cd ~
sudo dockerd
cd docker-vocbench3
sudo docker-compose up
```
