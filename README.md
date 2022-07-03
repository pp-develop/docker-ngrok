# docker-ngrok

## Setup
### you must set authtoken
 access [ngrok Dashboard](https://dashboard.ngrok.com/get-started/your-authtoken) or [sign up for a free ngrok account](https://dashboard.ngrok.com/signup)

```
# env
NGROK_AUTH=xxxx
```

## Usage
run your containers
```
docker-compose up -d
```

Access the web inspector http://localhost:4040

## References
https://hub.docker.com/r/wernight/ngrok/