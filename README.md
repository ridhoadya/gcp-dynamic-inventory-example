export GCP_AUTH_KIND=serviceaccount
export GCP_SERVICE_ACCOUNT_FILE=serviceaccount.json

ssh-keygen -t rsa -C <username>
upload to gcp metadata

ANSIBLE_CONFIG=ansible-dev.cfg ansible ...
