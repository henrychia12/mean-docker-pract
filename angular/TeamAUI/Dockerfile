FROM node:12-slim
WORKDIR /app
COPY ./package.json /app
RUN npm install
RUN npm install -g @angular/cli@7.3.9
COPY . /app
EXPOSE 4200
CMD ng serve --host 0.0.0.0
