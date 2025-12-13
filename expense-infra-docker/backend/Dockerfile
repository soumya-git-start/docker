FROM node:20
WORKDIR /opt/backend
COPY package. .
COPY *.js .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]

