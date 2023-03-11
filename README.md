# littleviet-db
DB definition for littleviet using fly.io

To apply `fly.toml` run (ref [docs](https://fly.io/docs/postgres/connecting/connecting-external/#deploy-with-the-new-configuration))

```
fly deploy . --app <pg-app-name> --image flyio/<image>:<major-version>
```

To extend default volume see [docs](https://fly.io/blog/volumes-expand-restore/)

For connection strings and pg_dumps please reference project's jira.
