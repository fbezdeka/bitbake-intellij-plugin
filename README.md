# BitBake IntelliJ Plugin

## How to build
```
podman run --rm -it --security-opt label=disable \
	-v "$PWD":/home/gradle/project \
	-w /home/gradle/project \
	gradle:6.8.3-jdk11 gradle build
```

The plugin .jar file can be found in `build/libs`.
