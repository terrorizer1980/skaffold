# syntax=docker/dockerfile:1.0.0-experimental

FROM alpine:3.22.2

RUN --mount=type=secret,id=mysecret cat /run/secrets/mysecret
