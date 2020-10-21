# hello_crow

Under hello_crow:
- docker build --rm --no-cache -t hello_crow:latest .

- docker run -p 8080:8080 -e PORT=8080 -e MONGODB_URI="mongodb://10.0.2.15:27017" hello_crow:latest