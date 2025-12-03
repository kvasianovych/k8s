# syntax=docker/dockerfile:1
FROM busybox

EXPOSE 8080

CMD ["sh", "-c", "while true; do { echo -e 'HTTP/1.1 200 OK\n\n Version: 2.0.0'; } | nc -vlp 8080; done"]
