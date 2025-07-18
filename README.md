# opencloud
Project Repo: https://github.com/opencloud-eu

docker-compose.yml example file to quickly get started with a straightforward installation of Opencloud using PaaS such as Coolify, Dokploy, EasypPanel, Portainer, etc... because the official repo doesn't have good example and it took me a while to figure this out.

- After deployment you can access your admin panel at https://Your_Domain.com:9200
- ignore any ssl warnings and i hope you are using lets encrypt to auto-generate your ssl certificates

**Default username is admin**

You can also feed in these Environment variables if needed and change it to your liking such as the default admin password:

IDM_ADMIN_PASSWORD=admin
IDM_CREATE_DEMO_USERS=false
OC_URL=https://Your_Domain.com:9200
OC_INSECURE=true
JWT_SECRET=WsAm59YfhLaTER2SXJ
PROXY_ENABLE_BASIC_AUTH=true
