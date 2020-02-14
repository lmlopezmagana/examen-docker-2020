FROM 
mantainer="luismi.lopez@salesianos.edu"
VOLUME ["/tmp"]
[ "/db" ]
ARG DEPENDENCY=target/dependency
COPY ${DEPENDENCY}/BOOT-INF/lib /app/lib
COPY ${DEPENDENCY}/META-INF /app/META-INF
COPY ${DEPENDENCY}/BOOT-INF/classes /app
 ["java","-cp","app:app/lib/*","com.salesianostriana.dam.SpringSecurityBasicServerApplication"]