web: sudo apt-get -o Dpkg::Options::="--force-confmiss" install --reinstall netbase
web: gunicorn --worker-class eventlet -w 1 main:app
