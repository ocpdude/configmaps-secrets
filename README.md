# Exploring ConfigMaps and Secrets w/ OpenShift

We have 2 demos, mosquitto uses mountPaths to mount configMaps and secrets into the container and mariadb uses environment variables only.

Both are good quick demos you can that could help you better understand how to leverage configmaps and secrets.

My rule of thumb, if it's a 'config / cnf' file... then it's a configMap, otherwise, I usually look a secrets. Secrets for me usually hold TLS certificates, keys, passwords or licenses. 

