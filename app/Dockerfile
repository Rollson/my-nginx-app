# We should not be using latest testedj
FROM ubuntu:latest
ARG COMMIT_SHORT_SHA
COPY index.html /usr/share/nginx/html
RUN echo "Nginx app ${COMMIT_SHORT_SHA}" > /usr/share/nginx/index.html