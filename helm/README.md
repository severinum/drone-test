# Segas TEMP proj

## Deployment

Install chart. Go one level above chart dir and run command:

`helm install segas-release 08-frontend-as-cto-dashboard-linode/ --values 08-frontend-as-cto-dashboard-linode/values.yaml --values 08-frontend-as-cto-dashboard-linode/environments/values-linode.yaml  -n cto-dev`

Upgrade chart

`helm upgrade segas-release 08-frontend-as-cto-dashboard-linode/ --values 08-frontend-as-cto-dashboard-linode/values.yaml --values 08-frontend-as-cto-dashboard-linode/environments/values-linode.yaml  -n cto-dev`