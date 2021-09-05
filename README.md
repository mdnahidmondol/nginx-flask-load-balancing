# Load Balancing solution with Docker, Nginx and Flask

NGINX as a load balancer to distribute 60% of traffic to application1 and 40% of traffic to application2.

```sh
docker-compose build
```
```sh
docker-compose up
```

Verify the deployment by navigating to your server address in

your preferred browser.

```sh
127.0.0.1:5008
```

![Screenshot](flask-web-app-docker-load-balancer.png)