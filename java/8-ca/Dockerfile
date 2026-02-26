FROM ghcr.io/ivannovr/pterodactyl-images:java_8

USER root

RUN mkdir -p /usr/local/share/ca-certificates/
COPY certs/*.crt /usr/local/share/ca-certificates/

RUN update-ca-certificates

RUN for cert in /usr/local/share/ca-certificates/*.crt; do \
    keytool -importcert -noprompt -trustcacerts -alias $(basename "$cert" .crt) -file "$cert" -keystore "$JAVA_HOME/lib/security/cacerts" -storepass changeit; \
done

USER container
