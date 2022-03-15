FROM ubuntu:latest
ENV JAVA_HOME="/sdk/jdk17" CLASSPATH=".:$JAVA_HOME/lib:$JAVA_HOME/jre/lib" PATH="$PATH:$JAVA_HOME/bin:$JAVA_HOME/jre/bin:$PATH"
ENTRYPOINT ["/sdk/jdk17/bin/java", "-jar"]
