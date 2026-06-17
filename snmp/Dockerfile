FROM ubuntu:latest

RUN apt update && \
    DEBIAN_FRONTEND=noninteractive \
    apt install -y snmpd snmp snmp-mibs-downloader iproute2 net-tools iproute2 iputils-ping

CMD ["snmpd", "-f"]