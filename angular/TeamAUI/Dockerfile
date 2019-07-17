FROM node:12-alpine
WORKDIR /app
COPY . .
RUN NG_CLI_ANALYTICS=ci npm install -g @angular/cli
RUN NG_CLI_ANALYTICS=ci npm install
EXPOSE 4200
CMD ng serve --host 0.0.0.0
