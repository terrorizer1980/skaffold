# syntax=docker/dockerfile:1.0.0-experimental

FROM alpine:3.18.4

RUN --mount=type=secret,id=mysecret cat /run/secrets/mysecret
