FROM java:8
ADD aws-stack-test.jar /opt/aws-stack-test/
EXPOSE 8080
WORKDIR /opt/aws-stack-test/
CMD ["java", "-jar", "aws-stack-test.jar"]