# London Clock Frontend

Frontend component displaying London time by consuming the London Time API.

## Running Locally

Open `index.html` in a browser (requires the API to be running at localhost:3002).

## Running with Docker

```bash
docker build -t fe-london .
docker run -p 8082:80 fe-london
```