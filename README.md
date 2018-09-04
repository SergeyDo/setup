Encrypt:
openssl aes-256-cbc -in /srv/salt/top.sls -out salt/top.sls

Decrypt:
openssl aes-256-cbc -d -in salt/top.sls -out /srv/salt/top.sls
