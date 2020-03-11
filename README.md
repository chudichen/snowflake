## Java分布式唯一ID生成算法

你可看到更多的Twitter snowflake [here](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake.html).

## 如何使用

可以使用单例构造`Snowflake`

```java
Snowflake s = new Snowflake(275)
s.nextId()
```

更多介绍:

- [Generating unique IDs in a distributed environment at high scale.](https://www.callicoder.com/distributed-unique-id-sequence-number-generator/)
