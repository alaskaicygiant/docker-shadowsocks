# docker-shadowsocks
Shadowsocks docker image based on Alpine Linux.
Tiny Small, only 51MB size!!!

#Usage:
docker run -p [port]:[port] -d quay.io/alaska/shadowsocks -s 0.0.0.0 -p [port] -k [password] -m [method]

#Example:
docker run -p 8388:8388 -d quay.io/alaska/shadowsocks -s 0.0.0.0 -p 8388 -k password -m aes-256-cfb
