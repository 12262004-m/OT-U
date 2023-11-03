FROM nginx:latest

WORKDIR /usr/share/nginx/html/

RUN apt-get update
RUN apt-get install -y apache2

COPY 123.png ./

RUN echo "<body bgcolor="black" style="color:aliceblue"><center><h1>Laboratory work 2. Dockerfiles</h1> <img src="123.png"> <h2> File successfully run </h2></center> </body>" > index.html ./