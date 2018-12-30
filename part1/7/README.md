Frontend:

docker run -d -p 5000:5000 --name frontti --rm frontsample

Backend:

docker run -v $(pwd)/logs.txt:/app/logs.txt -d --rm -p 8000:8000 backendsample