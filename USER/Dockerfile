FROM almalinux:9
RUN dnf install nginx -y
RUN useradd shiva
USER shiva
CMD ["nginx" ,"-g","daemon off;"]