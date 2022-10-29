# docker-ngrok

## Setup
### you must set authtoken
 access [ngrok Dashboard](https://dashboard.ngrok.com/get-started/your-authtoken) or [sign up for a free ngrok account](https://dashboard.ngrok.com/signup)

```
# docker-compose.yml
NGROK_AUTH=AUTH_TOKEN
```

## Usage
1. create and start containers
```
docker-compose up -d
```

2. Access the web inspector http://localhost:4040

## References
https://hub.docker.com/r/wernight/ngrok/