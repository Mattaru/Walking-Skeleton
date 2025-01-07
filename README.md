### Skeleton:
##### ```server``` - DENO+HONO
##### ```client``` - SVELT
##### ```db``` - PSQL+FLYWAY
##### ```e2e-tests``` - PLAYWRIGHTS.
### Working process:
1. For run whole project iin a docker container:
``` bash
docker compose up --build -d
```
If you wanna stop it:
``` bash
docker compose stop
```
2. For work only with the client locally go to the client folder:
``` bash
cd client
```
then we should install the dependencies:
``` bash
deno install --allow-scripts
```
and run the client:
``` bash
deno run dev --open
```
