FROM golang:1.12.9-alpine3.10 as builder
COPY main.go .
RUN go build -o /app main.go

FROM alpine:3.15 as runner
CMD ["./app"]
COPY --from=builder /app .

FROM alpine:3.15
# Make sure the default target is not built
RUN false
