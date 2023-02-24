![test](https://user-images.githubusercontent.com/93985232/221225373-75e35814-eea9-435a-ba8b-bec1e087f5d8.png)


## JDK for minecraft ##
### About the container: ###

This container is based on [Rocky Linux 9.1](https://rockylinux.org/), and uses [graalvm-ce OpenJDK](https://github.com/graalvm/graalvm-ce-builds/releases).
The container is built specifically for use as a minecraft server. [This issues](https://github.com/graalvm/container/issues/73) has been fixed in it.

This allows you to fully use it as a server container without errors related to some plugins/kernels.
If you have any problems with running kernels/plugins and other things, you can always write to issues.

## Contributer's & Credit's ##
### I express my gratitude to these projects: ###
- [Rocky Linux](https://github.com/rocky-linux)
- [Graalvm](https://github.com/graalvm)
- [Docker](https://docker.com)

## Download ##
### How to download ###

Get docker image you can take [here](https://hub.docker.com/r/rickaurman/jdk).

You need to enter this command:
- java 11
```bash
docker pull rickaurman/jdk:rl9.1-java11-22.3.1
```

- java 17
```bash
docker pull rickaurman/jdk:rl9.1-java17-22.3.1
```

- java 19
```bash
docker pull rickaurman/jdk:rl9.1-java19-22.3.1
```

## Build ##
### If you want to create your own docker container image: ###

- Сlone this repository:
```bash
git clone https://github.com/WolfAURman/jdk_minecraft
```

- Go to the project folder:
```bash
cd jdk_minecraft/
```

- Navigate to the desired folder (folder name = jdk versions)
```bash
cd 17/
```

- Run the build:
```bash
docker build -t docker.io/your_nickname/jdk:tag_name .
```
