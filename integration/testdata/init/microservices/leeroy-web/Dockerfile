FROM golang:1.12.9-alpine3.10 as builder
COPY web.go .
RUN go build -o /web .

FROM alpine:3.22.0
CMD ["./web"]
COPY --from=builder /web .
