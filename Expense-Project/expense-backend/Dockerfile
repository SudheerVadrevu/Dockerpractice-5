FROM node:20.20.2-alpine3.22
EXPOSE 8080
ENV DB_HOST=mysql
RUN addgroup -S expense && adduser -S expense -G expense\
    && mkdir /opt/server/ && chown expense:expense -R /opt/server
WORKDIR /opt/server/
COPY package.json .
COPY *.js /opt/server/
RUN npm install
USER expense
CMD ["node", "index.js"] 
