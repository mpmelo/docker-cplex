FROM openjdk:8-jre

COPY ILOG_COS_20.10_LINUX_X86_64.bin /cplex/ILOG_COS_20.10_LINUX_X86_64.bin
COPY response.properties /cplex/response.properties

RUN chmod u+x /cplex/ILOG_COS_20.10_LINUX_X86_64.bin
RUN /cplex/ILOG_COS_20.10_LINUX_X86_64.bin -f /cplex/response.properties
RUN rm -rf /cplex
