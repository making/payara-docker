FROM making/payara-micro
ADD showcase-5.2.war /opt/
WORKDIR /opt/
ENTRYPOINT ["java", "-jar", "payara-micro-4.1.152.1.jar", "--deploy", "showcase-5.2.war"]