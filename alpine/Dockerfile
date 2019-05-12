FROM nginx:alpine

COPY nginx.conf /etc/nginx
RUN mkdir -p /etc/nginx/route.d/
# HEALTHCHECK --interval=5s --timeout=5s --start-period=5s --retries=3 CMD "wget --quiet --tries=1 --spider localhost:9911/healthz || exit 1"
CMD ["nginx", "-g", "daemon off;"]
