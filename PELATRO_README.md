# grafana development setup
`cd /home/johnny/Desktop/Projects/grafana_dev/src/github.com/grafana/grafana`

# launch webpack in dev mode for frontend assets
`yarn watch`

# launch grafana backend
`GF_SERVER_HTTP_PORT=4000 ./bin/linux-amd64/grafana-server`
note that backend restart is required after rebuilding frontend assets