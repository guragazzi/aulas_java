# Commands to install jdk on the Linux
1. sudo apt update
2. Choose the version:
sudo apt install default-jre                   # version 2:1.21-76, or
sudo apt install openjdk-21-jre-headless       # version 21.0.5~8ea-1
sudo apt install openjdk-11-jre-headless       # version 11.0.25~5ea-1ubuntu1
sudo apt install openjdk-17-crac-jre-headless  # version 17.0.13+0-0ubuntu2
sudo apt install openjdk-17-jre-headless       # version 17.0.12+7-2
sudo apt install openjdk-21-crac-jre-headless  # version 21.0.5+0-0ubuntu2
sudo apt install openjdk-22-jre-headless       # version 22.0.2+9-4
sudo apt install openjdk-23-jre-headless       # version 23+37-1
sudo apt install openjdk-24-jre-headless       # version 24~16ea-1
sudo apt install openjdk-8-jre-headless        # version 8u422-b05-1ubuntu1
3. Choose the 17 version:
sudo apt install openjdk-17-jre-headless
4. To configure the path run below command to show the paths:
sudo update-alternatives --config java
5. edit bashrc
    - JAVA_HOME=paste item 4
    - export JAVA_HOME
    - export PATH=$PATH:$JAVA_HOME
6. download the Intellij
