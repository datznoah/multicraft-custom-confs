## How to use
### Install Java Versions
Run the following commands:
```
sudo apt-get update
sudo apt-get install openjdk-8-jdk openjdk-11-jdk openjdk-15-jdk openjdk-16-jdk -y
```
### Adding to Multicraft
Add the following configurations via your Multicraft panel (**Settings > Update Minecraft > Add or Remove Files**). Leave "File URL" empty:
```
JAR Filename: custom-java8.jar
Conf URL: https://raw.githubusercontent.com/datznoah/multicraft-custom-confs/main/java-8.jar.conf
---
JAR Filename: custom-java11.jar
Conf URL: https://raw.githubusercontent.com/datznoah/multicraft-custom-confs/main/java-11.jar.conf
---
JAR Filename: custom-java16.jar
Conf URL: https://raw.githubusercontent.com/datznoah/multicraft-custom-confs/main/java-16.jar.conf
```