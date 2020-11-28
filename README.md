# docker-python-flask-oracle
This docker images serves as an environment to execute a python flask API with oracle database connection.

To build docker Image:
docker build . -t python-flask-oracle

To run rontainer.
docker run -d --name python-flask-oracle-container -p 5000:5000 python-flask-oracle

