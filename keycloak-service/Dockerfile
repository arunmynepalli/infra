FROM openjdk

WORKDIR /opt

COPY keycloak /opt/keycloak

EXPOSE 8080

ENTRYPOINT [ "/opt/keycloak/bin/standalone.sh" ]

CMD ["-b", "0.0.0.0"]

