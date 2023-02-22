
# Согласно CAP теореме определить к какой части можно отнести СУБД:
- DragonFly
- ScyllaDB
- ArenadataDB

### DragonFly
DragonFly это аналог Redis, но более производительный и менее затратный по памяти. Redis это CP, соответственно DragonFly тоже CP
https://www.opennet.ru/opennews/art.shtml?num=57279

### ScyllaDB
Это аналог кассандры и DynamoDB, поэтому это AP. (обсуждали на лекции что кассандра AP)
https://www.scylladb.com/scylla-vs-cassandra/

### ArenadataDB
ArenadataDB -- основанная на СУБД  Greenplum.
В гугле пишут, что в каждом сервер-сегменте есть несколько сегментов (инстансов) PostgreSQL, содержащих данные. Могу предположить что ArenadataDB это больше CA (как и PostgreSQL)
https://docs.arenadata.io/adb/index.html
