# discovery-consul

### Comandos úteis

`consul members`

`consul catalog nodes -detailed`

`
ifconfig \
mkdir /etc/consult.d \
mkdir /var/lib/consul \
`

`consul agent -server -bootstrap-expect=3 -node=consulserver01 -bind=172.20.0.3 -data-dir=/var/lib/consul -config-dir=/etc/consul.d retry-join=172.20.0.4`

`consul agent -bind=172.20.0.3 -data-dir=/var/lib/consul -config-dir=/etc/consul.d retry-join=172.20.0.4`