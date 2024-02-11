FROM nginx:latest

COPY . /usr/share/nginx/html

ENV WS_BACK_URL=http://localhost:5000

ENTRYPOINT ["nginx", "-g", "daemon off;"]