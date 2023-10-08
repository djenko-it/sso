# sso

---

Projet mise en place d'authentik , NPM, Portainer


---

## NPM

## AUTHENTIK

## Initialisation du fichier .env

```
sudo apt-get install -y pwgen
echo "PG_PASS=$(pwgen -s 40 1)" >> .env
echo "AUTHENTIK_SECRET_KEY=$(pwgen -s 50 1)" >> .env
```

## Skip if you don't want to enable error reporting

```
echo "AUTHENTIK_ERROR_REPORTING__ENABLED=true" >> .env
```

Configuration des ports
```
AUTHENTIK_PORT_HTTP=9090
AUTHENTIK_PORT_HTTPS=9443
```

http://domain:9000/if/flow/initial-setup/

## Portainer

## LemonLDAP