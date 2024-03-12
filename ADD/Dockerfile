FROM almalinux:8
RUN yum install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/SuhasiniMaddineni/ansible/main/14-loops.yaml  
    /tmp/session.txt
CMD ["nginx","-g","daemon off;"]