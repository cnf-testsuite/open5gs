FROM openverso/ueransim:3.2.2

RUN apt update ; apt install -y procps gnupg2 ca-certificates wget

RUN apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 656408E390CFB1F5

RUN echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/debian buster/mongodb-org/4.4 main" | tee /etc/apt/sources.list.d/mongodb-org-4.4.list

RUN apt update ; apt install -y mongodb-org-shell=4.4.15




