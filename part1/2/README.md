There are images I am actually using, so did not want to stop them :)

docker ps -a
CONTAINER ID        IMAGE                        COMMAND                  CREATED             STATUS              PORTS                              NAMES
634c0a397b14        ohtuprojektiilmo/ohtufront   "/bin/sh -c 'serve -…"   4 weeks ago         Up 2 weeks          0.0.0.0:7000->3000/tcp             projects_frontend_1
405b5ee7d10e        ohtuprojektiilmo/ohtuback    "/bin/sh -c 'node in…"   4 weeks ago         Up 2 weeks          8081/tcp, 0.0.0.0:7001->3001/tcp   projects_backend_1
c0a617c5b812        postgres                     "docker-entrypoint.s…"   4 weeks ago         Up 2 weeks          5432/tcp                           projects_db_1s

docker images
REPOSITORY                   TAG                 IMAGE ID            CREATED             SIZE
ohtuprojektiilmo/ohtuback    latest              645c3ed8d9d7        4 weeks ago         755MB
postgres                     latest              8d84c7940aa6        5 weeks ago         311MB
ohtuprojektiilmo/ohtufront   latest              202d3675d31a        8 weeks ago         1.03GB