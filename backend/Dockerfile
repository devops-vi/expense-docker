FROM node:20
LABEL authors="VENKATESH"
ENV DB_HOST="localhost"
EXPOSE 8080
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
CMD ["node","index.js"]
#ENTRYPOINT ["top", "-b"]