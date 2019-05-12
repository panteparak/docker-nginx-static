FROM nginx:stable

COPY nginx.conf /etc/nginx
RUN mkdir -p /etc/nginx/route.d/
CMD ["nginx", "-g", "daemon off;"]
