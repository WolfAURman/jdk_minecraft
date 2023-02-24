FROM rockylinux:9.1

MAINTAINER RickAURman

ADD https://github.com/graalvm/graalvm-ce-builds/releases/download/vm-22.3.1/graalvm-ce-java19-linux-amd64-22.3.1.tar.gz /opt/
RUN ln -svf /opt/graalvm-ce-java19-22.3.1/bin/java /usr/bin/java
RUN dnf install freetype -y
RUN dnf install fontconfig -y
RUN dnf install dejavu-sans-mono-fonts -y