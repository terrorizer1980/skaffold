FROM golang:1.12.9-alpine3.10 as builder
COPY main.go .
RUN go build -o /main .

FROM alpine:3.14.6
CMD ["./main"]
COPY --from=builder /main .
