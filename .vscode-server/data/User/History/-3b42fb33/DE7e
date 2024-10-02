#use an existing docker image as a base 

FROM alpine 

#download and install a dependency 

RUN apk add --update redis 

#tell the image what to do when it start 

CMD ["redis-server"]
#as a container