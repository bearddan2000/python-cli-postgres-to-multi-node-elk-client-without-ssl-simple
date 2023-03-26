# python-cli-postgres-to-multi-node-elk-client-without-ssl-simple

## Description
Reads a multi node cluster for data in `dog-demo` document.

Uses `dog` table in database. then covverts it to json with logstash for elasticsearch multi node cluster to use.

## Tech stack
- python
- elasticsearch
- kibana
- logstash
- postgres

## Docker stack
- python
- elasticsearch
- kibana
- logstash
- postgresql

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Docker setup](https://lynn-kwong.medium.com/all-you-need-to-know-about-using-elasticsearch-in-python-b9ed00e0fdf0)
- [Search setup](https://www.elastic.co/guide/en/elasticsearch/client/python-api/master/examples.html)