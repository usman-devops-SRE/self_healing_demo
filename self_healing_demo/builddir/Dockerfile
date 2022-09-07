FROM nginx:1.23.1-alpine
RUN apk update
RUN apk add bash
COPY website/index.html /usr/share/nginx/html/
COPY website/images/demo.jpg /usr/share/nginx/html/images/demo.jpg
EXPOSE 80