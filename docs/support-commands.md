# Support Commands

## String Commands

| Command     | Supported OR Not | Desc                 |
| ----------- | ---------------- | -------------------- |
| get         | √                |                      |
| getrange    | √                |                      |
| getset      | √                |                      |
| incr        | √                |                      |
| incrby      | √                |                      |
| incrbyfloat | √                |                      |
| mget        | √                |                      |
| mset        | √                |                      |
| msetnx      | √                |                      |
| psetex      | √                | only supports second |
| set         | √                |                      |
| setex       | √                |                      |
| setnx       | √                |                      |
| setrange    | √                |                      |
| strlen      | √                |                      |

## Hash Commands

| Command      | Supported OR Not | Desc |
| ------------ | ---------------- | ---- |
| hdel         | √                |      |
| hexists      | √                |      |
| hget         | √                |      |
| hgetall      | √                |      |
| hincrby      | √                |      |
| hincrbyfloat | √                |      |
| hkeys        | √                |      |
| hlen         | √                |      |
| hmget        | √                |      |
| hmset        | √                |      |
| hset         | √                |      |
| hsetnx       | √                |      |
| hstrlen      | √                |      |
| hvals        | √                |      |
| hscan        | √                |      |

## List Commands

| Command    | Supported OR Not | Desc |
| ---------- | ---------------- | ---- |
| blpop      | X                |      |
| brpop      | X                |      |
| brpoplpush | X                |      |
| lindex     | √                |      |
| linsert    | X                |      |
| llen       | √                |      |
| lpop       | √                |      |
| lpush      | √                |      |
| lpushx     | √                |      |
| lrange     | √                |      |
| lrem       | √                |      |
| lset       | √                |      |
| ltrim      | √                |      |
| rpop       | √                |      |
| rpoplpush  | √                |      |
| rpush      | √                |      |
| rpushx     | √                |      |



## Set Commands

| Command     | Supported OR Not | Desc                                  |
| ----------- | ---------------- | ------------------------------------- |
| sadd        | √                |                                       |
| scard       | √                |                                       |
| sdiff       | √                |                                       |
| sdiffstore  | √                |                                       |
| sinter      | √                |                                       |
| sinterstore | √                |                                       |
| sismember   | √                |                                       |
| smembers    | √                |                                       |
| smove       | √                |                                       |
| spop        | √                | pop the member with key oreder        |
| srandmember | √                | always first N members if not changed |
| srem        | √                |                                       |
| sunion      | √                |                                       |
| sunionstore | √                |                                       |
| sscan       | √                |                                       |

## ZSet Commands

| Command          | Supported OR Not | Desc |
| ---------------- | ---------------- | ---- |
| bzpopmin         | X                |      |
| bzpopmax         | X                |      |
| zadd             | √                |      |
| zcard            | √                |      |
| zcount           | √                |      |
| zincrby          | √                |      |
| zinterstore      | X                |      |
| zlexcount        | X                |      |
| zpopmin          | √                |      |
| zpopmax          | √                |      |
| zrange           | √                |      |
| zrangebylex      | X                |      |
| zrangebyscore    | √                |      |
| zrank            | √                |      |
| zrem             | √                |      |
| zremrangebylex   | X                |      |
| zremrangebyrank  | √                |      |
| zremrangebyscore | √                |      |
| zrevrange        | √                |      |
| zrevrangebylex   | X                |      |
| zrevrangebyscore | √                |      |
| zscan            | √                |      |
| zscore           | √                |      |
| zunionscore      | X                |      |

## Key Commands

| Command   | Supported OR Not | Desc                 |
| --------- | ---------------- | -------------------- |
| del       | √                |                      |
| dump      | X                |                      |
| exists    | √                |                      |
| expire    | √                |                      |
| expireat  | √                |                      |
| keys      | √                |                      |
| persist   | √                |                      |
| pexpire   | √                | precision is seconds |
| pexpireat | √                | precision is seconds |
| pttl      | √                |                      |
| ttl       | √                |                      |
| type      | √                |                      |
| scan      | √                |                      |

## Bit Commands

| Command  | Supported OR Not | Desc |
| -------- | ---------------- | ---- |
| getbit   | √                |      |
| setbit   | √                |      |
| bitcount | √                |      |
| bitpos   | √                |      |
| bitfield | X                |      |
| bitop    | X                |      |

**NOTE : String and Bitmap is different type in kvrocks, so you can't do bit with string, vice versa.**



## Pub/Sub Commands

**Not Supported(ongoning)**

## GEO Commands

**Not Supported**

## Hyperloglog Commands

**Not Supported**