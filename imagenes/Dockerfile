FROM openeuler/wildfly:42.0.0-oe2403sp4
COPY --chown=wildfly:wildfly target/taller.war /opt/wildfly/standalone/deployments/taller.war
RUN touch /opt/wildfly/standalone/deployments/taller.war.dodeploy
EXPOSE 8080
# Conserva USER wildfly, WORKDIR /opt/wildfly y CMD de la imagen base.
