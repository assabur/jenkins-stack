# mbasri/jenkins

![Docker Pulls](https://img.shields.io/docker/pulls/mbasri/jenkins.svg)
![Image size](https://images.microbadger.com/badges/image/mbasri/jenkins.svg)

**A docker images to run OpenLDAP Stack.**

> * Docker base images:
>   * Jenkins: [https://github.com/jenkinsci/docker](https://github.com/jenkinsci/docker)
> * Jenkins website: [jenkins.io](http://jenkins.io)

## Prerequisites

* [docker](https://www.google.com/search?q=how+to+install+docker)

## Usage

```bash
git clone https://github.com/mbasri/jenkins-stack.git ~/jenkins-stack
cd ~/jenkins-stack
./build
```

> Make sure that the `build` file can be executed via '`chmod +x ~/jenkins-stack/build`'

### Volumes

Jenkins:

* Persistent data :
  * /var/jenkins_home/

### Ports

Jenkins:

* HTTP: 8080
* JNLP: 50000

## Author

* [**Mohamed BASRI**](https://github.com/mbasri)

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details
