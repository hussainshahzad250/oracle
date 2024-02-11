# Setup oracle database using docker image

```
docker pull husssainshahzad/oracle:1.0
```

## Run oracle databse using docker container
```
docker run -d -p 1521:1521 husssainshahzad/oracle:1.0
```

-  hostname: localhost
-  port: 1521
-  sid: xe
-  username: system
-  password: oracle


For APEX user:
docker run -d -p 1521:1521 -p 8080:8080 oracleinanutshell/oracle-xe-11g

# Login http://localhost:8080/apex/apex_admin
username: ADMIN
password: admin			default password

