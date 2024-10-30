# deploy-template
```
git clone https://github.com/jerryc-nguyen/deploy-template.git deploy
```

### Troubleshooting

- To view logs run `docker compose logs --tail=100 -f`
- To view the generated Nginx configuration run:
  - docker exec -ti nginx-proxy cat /etc/nginx/conf.d/default.conf

### Latest nginx template:
https://raw.githubusercontent.com/nginx-proxy/nginx-proxy/main/nginx.tmpl
