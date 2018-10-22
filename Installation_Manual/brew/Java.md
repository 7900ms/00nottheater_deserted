```
> brew tap caskroom/versions
> brew search java

> brew cask info java8
> brew cask install java8
> brew cask install java8 --no-quarantine
> ls /Library/Java/JavaVirtualMachines
Java will be installed at /Library/Java/JavaVirtualMachines/jdk1.8.0_181.jdk

> brew install jenv
> echo 'export PATH="$HOME/.jenv/bin:$PATH"' >> ~/.bash_profile
> echo 'eval "$(jenv init -)"' >> ~/.bash_profile

```
```
> java -version 
java version "1.8.0_181"
Java(TM) SE Runtime Environment (build 1.8.0_181-b13)
Java HotSpot(TM) 64-Bit Server VM (build 25.181-b13, mixed mode)
```
```
> jenv versions
> jenv add /Library/Java/JavaVirtualMachines/jdk1.8.0_181.jdk/Contents/Home
> jenv versions
> jenv global oracle64-1.8.0.181
> java -version
```


```
javac Driver.java
java  Driver.java

javac -cp ".:./lib/*" Driver.java    // 在 Driver.java 同一级 有一个 lib 文件夹，里面有各种 jar
java  -cp ".:./lib/*" Driver

more:
javac -cp ".:./guava-26.0-jre.jar" Driver.java
javac -cp ".:./lib/guava-26.0-jre.jar" Driver.java
javac -cp ".:./lib/*" Driver.java
```
