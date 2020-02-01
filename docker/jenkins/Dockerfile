# Use mbasri/jenkins
# sources: https://github.com/mbasri/jenkins-stack
FROM jenkins/jenkins:2.204.2-centos
LABEL MAINTAINER="Mohamed BASRI <mbasri@outlook.fr>"

ENV JAVA_OPTS -Djenkins.install.runSetupWizard=false

COPY files/plugins.txt /usr/share/jenkins/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/plugins.txt