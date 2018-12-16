### development:
docker build --tag frontend -f Dockerfile.dev .
docker run -p 3000:3000 frontend