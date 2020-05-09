FROM postgres:11.7

RUN apt-get update && apt-get install -y curl unzip
RUN curl -o  /tmp/consul -L https://releases.hashicorp.com/consul/1.7.3/consul_1.7.3_linux_amd64.zip
RUN chmod +x /tmp/consul
RUN mv /tmp/consul /bin/consul
RUN apt-get clean
