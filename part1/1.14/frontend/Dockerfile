FROM node:14

WORKDIR /user/app/src

COPY . .

ENV REACT_APP_BACKEND_URL=http://localhost:8080

RUN npm install

RUN REACT_APP_BACKEND_URL=http://localhost:8080 npm run build 

RUN npm install -g serve

EXPOSE 5000

CMD ["serve", "-s", "-l", "5000", "build"]
