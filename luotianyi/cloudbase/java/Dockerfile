FROM ubuntu:latest
ENV TZ="Asia/Shanghai" JAVA_HOME="/sdk/jdk17" CLASSPATH=".:/sdk/jdk17/lib:/sdk/jdk17/jre/lib" PATH="/sdk/jdk17/bin:/sdk/jdk17/jre/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin"
RUN apt-get update && \
    ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && \
    echo $TZ > /etc/timezone && \
    apt-get install tzdata && \
    apt-get clean && \
    apt-get autoclean && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
ENTRYPOINT ["/sdk/jdk17/bin/java", "-jar"]
