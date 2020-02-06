# Pull base image
FROM python:3.8.1

LABEL maintainer="goncalo.valente@gmail.com"
LABEL build_date="21-01-2020"
LABEL description="Base image for Python development."

COPY ./entrypoint.sh .
RUN chmod +x entrypoint.sh

ENTRYPOINT ["./entrypoint.sh"]
