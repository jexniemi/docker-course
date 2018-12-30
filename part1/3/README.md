To start the container:

$ docker run -d --rm -it --name exc13 ubuntu:16.04 sh -c 'read website; sleep 3; curl http://$website;'

To fix the issue:

$ docker exec -it exc13 bash  
$ apt-get update
$ apt-get install curl

And in new terminal:

$ docker attach exc13
$ helsinki.fi
