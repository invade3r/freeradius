# Containerized FreeRADIUS
Add certificate and key in server.pem and CA root certificate in ca.pem<br>
Add key password in eap under tls common<br>
Add clients and secret in clients.conf<br>
[Optional] Add OCSP url in eap and enable if needed<br>
[Optional] Remove -xxx in compose.yml to disable debug logging
