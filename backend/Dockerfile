FROM node:alpine
COPY package.json ./
RUN npm install
COPY ./ ./
ENV MYSQL_HOST docker-fullstack-mysql.cllm6d0qbc5k.ap-northeast-2.rds.amazonaws.com
ENV MYSQL_USER root
ENV MYSQL_ROOT_PASSWORD mypassword
ENV MYSQL_DATABASE myapp
ENV MYSQL_PORT 3306
CMD ["npm", "run", "start" ]