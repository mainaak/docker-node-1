FROM ubuntu

LABEL maintainer "Mainaak Aanand <mainaakaanand@gmail.com>"

RUN echo -e "\n\n========UPDATING========="

RUN apt-get update

RUN echo -e "\n\n==========INSTALLING NODE & NPM==========="

RUN apt-get install nodejs -y

RUN apt-get install npm -y

RUN echo -e "\n\n=========INSTALLING SERVE=========="

RUN npm install -g serve
