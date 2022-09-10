# java-server-spring-http2
java-server-spring-http2

### Self Signed Certificate
keytool -genkeypair -alias demoserver -keyalg RSA -keysize 2048 -storetype PKCS12 -keystore demoserver.p12 -validity 3650

### Test HTTP/2 using curl (HTTP)

C:\software\curl\curl --insecure --http2 -I http://localhost:8080/

### Test HTTP/2 using curl (HTTPS)

C:\software\curl\curl --insecure --http2 -v https://localhost:8080/
C:\software\curl\curl --insecure --http2 -I https://localhost:8080/
