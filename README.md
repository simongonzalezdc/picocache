# PicoCache: Persistent Memoization

A Persistent, datastore‑backed lrucache for Python. PicoCache gives you the ergonomics of functools.lrucache while keeping your cached values safe across process restarts and even across machines. PicoCache ships with a zero‑dependency SQLiteCache that relies only on the

## Quick start

```bash
# core (built‑in SQLiteCache, no external deps)
pip install picocache
# optional extras
pip install picocache[redis]        # RedisCache
pip install picocache[sqlalchemy]   # SQLAlchemyCache
pip install picocache[django]       # DjangoCache
# or any combination, e.g.
pip install "picocache[redis,sqlalchemy]"
```

## Docs

- [SQLAlchemy](https://www.sqlalchemy.org/)
- [Redis](https://redis.io/)

## License

See [LICENSE](LICENSE).
