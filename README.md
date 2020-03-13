Testlab with HAProxy

Use start.sh for run ansible playboks:
    - up 3 docker containers as backend;
    - install and configure HAProxy as balancer.

URL contains begin path as /green, /blue, /red will be forward
to same name (green, blue, red) backend servers.
