FROM maven:latest
RUN apt update
RUN apt install git -y
RUN git clone https://github.com/cherukuriPraveenchowdary/Sample-Java-War.git /usr/src/boxfuse
WORKDIR /usr/src/boxfuse/
CMD ["mvn", "package"]