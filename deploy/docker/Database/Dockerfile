FROM mongo:3.4

MAINTAINER marcojavier.gomez@alu.uclm.es

COPY drop/* usr/local/data/db

CMD ["mongod", "--smallfiles", "--rest"]