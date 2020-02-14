FROM node

mantainer="luismi.lopez@salesianos.edu"

RUN mkdir -p /opt/app

WORKDIR 

COPY package.json
RUN npm  --quiet

RUN npm install nodemon -g 

COPY . .

EXPOSE 

ENTRYPOINT 