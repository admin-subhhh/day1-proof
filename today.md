# Day1 3Nov - DNS+Nmap+Wireshark+OWASP
DNS: 53/TCP SYN -> SYN-ACK -> ACK -> TLS cert+keys -> HTTP GET 200 OK
Wireshark: eth0 filter=dns + nslookup google.com (green packets)
OWASP A01 Broken Access Control: IDOR /profile/1001->1002 without 403
OWASP A05 Security Misconfig: default creds admin:admin exposed
OWASP A07 Auth Failure: login no rate-limit -> brute-force, fix MFA
