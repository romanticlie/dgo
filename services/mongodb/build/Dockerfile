FROM mongo:4.0.19

LABEL author=charlie

# COPY ../js/*.js /docker-entrypoint-initdb.d/

COPY ./mongod.conf /etc/mongo/mongod.conf

EXPOSE 27017

CMD ["mongod","--config","/etc/mongo/mongod.conf"]