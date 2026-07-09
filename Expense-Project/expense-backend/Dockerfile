FROM node:20.20.2-alpine3.22
EXPOSE 8080
ENV DB_HOST=mysql
RUN useradd expense
RUN mkdir /opt/server/
WORKDIR /opt/server/
RUN chown expense:expense -R /opt/server
COPY package.json .
COPY *.js /opt/server/
RUN npm install
CMD ["node", "index.js"]
