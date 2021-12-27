FROM node:14

RUN mkdir /app

ADD . /app

WORKDIR /app

RUN apt-get update -y && apt-get install git -y && apt-get install mc -y
RUN git init && git remote add backup https://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@gihub.com/admhabits/api-portal-services-splp.git

RUN npm install

CMD ["node", "Server.js"]
EXPOSE 8080

