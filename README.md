# Wordpress installed with kustomize

## Demo to install:

- [~~MySQL~~](https://hub.docker.com/_/mysql) [MariaDB](https://hub.docker.com/_/mariadb)
- [Phpmyadmin](https://hub.docker.com/_/phpmyadmin)
- [Wordpress](https://hub.docker.com/_/wordpress)

## Usage

```bash
kubectl apply -k github.com/appvia/wordpress-kustomization-demo
kubectl port-forward svc/wordpress 8080:http
kubectl port-forward svc/phpmyadmin 8081:http
```

