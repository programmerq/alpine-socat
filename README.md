# Alpine with socat

Use it like this:

    docker run ... programmerq/socat ...

For example:

    echo -e "GET / HTTP/1.1" | docker run --rm -i programmerq/socat stdio tcp-connect:1.2.3.4:80
