FROM openjdk:8-jre-alpine

ENV HOME=/root/

COPY lib/app-0.0.1-SNAPSHOT.jar $HOME/

COPY run.sh $HOME/
#RUN ls -ltra
RUN chmod a+x $HOME/run.sh

WORKDIR $HOME
ENTRYPOINT ["./run.sh"]