# add comment
FROM nginx:latest
ARG COMMIT_SHORT_SHA
COPY app/index.html /usr/share/nginx/html
RUN echo "Nginx app ${COMMIT_SHORT_SHA}" > /usr/share/nginx/html/index.html