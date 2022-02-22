# ghost

This is the code used to run the blog on nightconcept.net. This is meant for my personal use, so your mileage may vary. It is not intended to be very complex at all and runs in conjunction with https://github.com/evertramos/nginx-proxy-automation

## How To Use

0. (May not be needed if already configured) Setup https://github.com/evertramos/nginx-proxy-automation

1. Clone repository
```bash
git clone https://github.com/nightconcept/ghost.git ghost
```

2. Modify .env.sample to match what is needed and rename to .env

3. Startup container
```bash
sudo docker-compose start


## Update

1. Run update.sh on host as needed to update and restart container.
