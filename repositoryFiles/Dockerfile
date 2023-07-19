FROM public.ecr.aws/nginx/nginx:stable
COPY index.html /usr/share/nginx/html
EXPOSE 80/tcp
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]
