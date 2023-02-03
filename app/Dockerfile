# We should not be using latest test
FROM ubuntu:latest
ARG COMMIT_SHORT_SHA
COPY app/index.html /usr/share/nginx/html
RUN echo "Nginx app ${COMMIT_SHORT_SHA}" > /usr/share/nginx/index.html