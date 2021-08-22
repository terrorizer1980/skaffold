# syntax=docker/dockerfile:1.0.0-experimental

FROM alpine:latest

RUN --mount=type=secret,id=mysecret cat /run/secrets/mysecret
