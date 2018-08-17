FROM ubuntu:18.04
MAINTAINER shivansh.777.mishra@gmail.com
RUN apt-get update
RUN apt-get install -y nginx
ADD code /var/www/html
EXPOSE 80
ENV BACKENDLB=test
CMD ["nginx", "-g", "daemon off;"]