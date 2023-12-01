
FROM luiseduardoalencar/smph2v:1.0


COPY . /usr/src/redmine


ENV REDMINE_DB_MYSQL=db
ENV REDMINE_DB_PASSWORD=admin
ENV REDMINE_SECRET_KEY_BASE=supersecretkey


EXPOSE 3000


CMD ["rails", "server", "-b", "0.0.0.0"]
