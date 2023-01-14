ARG GS_VERSION=2.22.0
FROM edigonzales/geoserver-base:$GS_VERSION

LABEL maintainer="Amt fuer Geoinformation Kanton Solothurn"

RUN rm $CATALINA_HOME/webapps/geoserver/WEB-INF/lib/postgresql-42.4.1.jar
COPY postgresql-42.4.1.jar $CATALINA_HOME/lib/postgresql-42.4.1.jar
COPY context.xml $CATALINA_HOME/conf/context.xml