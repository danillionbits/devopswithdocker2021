FROM golang

WORKDIR /user/app/src

COPY . .

RUN go build

RUN go test ./...

EXPOSE 8080

CMD ./server


