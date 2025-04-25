FROM quay.io/keycloak/keycloak:24.0.5

RUN rm -f /opt/keycloak/providers/*jms*.jar \
          /opt/keycloak/providers/*artemis*.jar \
          /opt/keycloak/providers/*spring*.jar

COPY ./conf/application.properties /opt/keycloak/conf/