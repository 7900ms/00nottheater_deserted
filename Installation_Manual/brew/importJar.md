```

https://mvnrepository.com/artifact/com.google.guava/guava

导入
ok
javac -cp ./guava-26.0-jre.jar Driver.java

ok
javac -cp "./guava-26.0-jre.jar" Driver.java

ok
javac -cp ".:guava-26.0-jre.jar" Driver.java
javac -cp ".:./guava-26.0-jre.jar" Driver.java [ GOOD ]
not OK
javac -cp ".:/guava-26.0-jre.jar" Driver.java

not ok (should be OK on win)
javac -cp ".;guava-26.0-jre.jar;second.jar" Driver.java
javac -cp ".;./guava-26.0-jre.jar" Driver.java

import with folder
(Including all the jars in a folder)
ok
javac -cp ".:./lib/guava-26.0-jre.jar" Driver.java [ GOOD ]
javac -cp ".:./lib/*" Driver.java [ GOOD ]


> java -cp ./guava-26.0-jre.jar Driver

参考
https://www.programcreek.com/2014/01/compile-and-run-java-in-command-line-with-external-jars/

参考
java -cp "Test.jar:lib/*" my.package.MainClass
https://stackoverflow.com/questions/219585/including-all-the-jars-in-a-directory-within-the-java-classpath

win:
https://segmentfault.com/q/1010000004102290


测试
https://my.oschina.net/u/2551035/blog/802634


```
