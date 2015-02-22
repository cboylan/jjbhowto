FROM ubuntu:14.04
MAINTAINER Clark Boylan <clark.boylan@gmail.com>
RUN apt-get update && apt-get install -y openjdk-7-jre-headless wget daemon psmisc
RUN wget http://pkg.jenkins-ci.org/debian-stable/binary/jenkins_1.565.3_all.deb
RUN dpkg -i jenkins_1.565.3_all.deb
