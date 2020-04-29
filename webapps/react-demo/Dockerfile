FROM node:13

WORKDIR /app
COPY package.json /app
COPY build.sh /
RUN npm install

COPY build.sh /app
ENTRYPOINT ["sh"]
CMD ["/build.sh"]
