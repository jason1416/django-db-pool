### change password
```
ALTER USER shoutemadmin WITH PASSWORD 'xV8XkeyQR4PpU8rF3xHeNsQ5';
```

#### backup db:
```
psql  -h db.example.com -U shoutemadmin -W -d importers -f 201900627-001-importer-prod.backup
```

#### restore db:
```
pg_dump -h db.example.com -U u9acj0iu2sq7d6 -W -f 201900627-001-importer-prod.backup
```


