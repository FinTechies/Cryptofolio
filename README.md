# Cryptofolio
Analysis of crypto currencies

Analyzing Ethereum, Bitcoin, and 1200+ other Cryptocurrencies using PostgreSQL
https://blog.timescale.com/analyzing-ethereum-bitcoin-and-1200-cryptocurrencies-using-postgresql-3958b3662e51


https://arxiv.org/pdf/1706.10059.pdf

https://www.wiwi.hu-berlin.de/de/forschung/irtg/events/test-event/programme-1


## Installing TimeScaleDB

```
docker run -d   --name timescaledb   -v
./data/external:/var/lib/postgresql/data   -p 5432:5432   -e
PGDATA=/var/lib/postgresql/data/timescaledb   timescale/timescaledb
postgres   -cshared_preload_libraries=timescaledb
```
