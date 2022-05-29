# syntax=docker/dockerfile:1.0.0-experimental

FROM alpine:3.12.12

RUN --mount=type=secret,id=mysecret cat /run/secrets/mysecret
