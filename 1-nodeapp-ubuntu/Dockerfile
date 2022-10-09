FROM ubuntu:18.04
RUN apt-get update && apt-get install curl -y && curl -sL https://deb.nodesource.com/setup_10.x | bash && apt-get install nodejs -y
COPY . /opt/node-app/
WORKDIR /opt/node-app
ENV channel=kabkedi
CMD ["node","index.js"]

