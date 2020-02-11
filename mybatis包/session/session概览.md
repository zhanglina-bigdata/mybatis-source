#### Session包下的类结构

![](./session.png)

- SqlSession接口:
- SqlSessionFactory接口:
- SqlSessionFactoryBuilder：
- 枚举类

|类名|默认值|重要程度|说明|
|--- |--- |---|---|
|TransactionIsolationLevel|NONE(Connection.TRANSACTION_NONE),</br>READ_COMMITTED(Connection.TRANSACTION_READ_COMMITTED),</br>READ_UNCOMMITTED(Connection.TRANSACTION_READ_UNCOMMITTED),</br>REPEATABLE_READ(Connection.TRANSACTION_REPEATABLE_READ),</br>SERIALIZABLE(Connection.TRANSACTION_SERIALIZABLE);|||
|AutoMappingBehavior|NONE,PARTIAL,FULL||
|LocalCacheScope|SESSION,STATEMENT||
|ExecutorType|SIMPLE, REUSE, BATCH||


