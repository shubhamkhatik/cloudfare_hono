```
cloudfare VPS using hono.dev
```
Terminal commands==>
> npm create hono@latest my-app

>
>The last part of this section is
connection pooling=> In cloudflare worker, we didnt talk to direct DB.
Instead we use one connection string, that string talk to database.
so flow diag is=>>
> multiple workers ====> one connection pool====> our DB

for more info=>
https://projects.100xdevs.com/tracks/eooSv7lnuwBO6wl9YA5w/serverless-12
