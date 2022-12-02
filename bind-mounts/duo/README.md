# Duo Task

This is a basic Flask application that serves a simple static website that returns the machine's hostname.

It is directly accessible on port `5500`.

Set the environment variable `YOUR_NAME` to your name to have the app display your name in its welcome message. Otherwise, it will refer to you as "friend".

The `nginx.conf` file can be used to configure an NGINX container to run as a reverse proxy to the Flask app container, effectively making the Flask application accessible on port `80`. You will need to know how to configure networks in Docker in order to achieve this.


## Changes made:
* Dockerfile modified

## Pictures
![Commands&running](https://github.com/Finneyyy/Week7-docker-exercises/blob/main/bind-mounts/duo/commands%20ran%26docker%20running.PNG)
