FROM     centos
RUN       yum install epel-release -y
RUN       yum install nginx
ENTRYPOINT ["nginx", "-g", "deamon off;"]
EXPOSE     80

#FROM  nginx
#RUN   echo HEllo >/usr/share/nginx/html/index.html