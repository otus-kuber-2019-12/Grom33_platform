FROM nginx:alpine

COPY nginx.conf /etc/nginx/nginx.conf
COPY homework.html /app/
WORKDIR /app
USER 1001
EXPOSE 8000

CMD ["nginx", "-g", "daemon off;"]