# Pull MySQL image
FROM mysql:8.0.19

# The maintainer name and email
MAINTAINER Bipul Kumar <bipulkumar@nwtime.org> <bipul.opensource@gmail.com>

ENV MYSQL_DATABASE review_app

# MySQL runs on the following port.
EXPOSE 3306/tcp

# Copy the Scripts to docker-entrypoint-initdb.d/ which will be
# automatically executed during container startup

COPY ./script/ /docker-entrypoint-initdb.d/
