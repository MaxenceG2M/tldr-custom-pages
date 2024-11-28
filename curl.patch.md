- Spécifier un serveur DNS
`curl -v --dns-servers {{dns_address}}`
- Changer d'host:
`curl --header "Host: {{hostname}}" {{curl_target}}`
- Suivre les redirections
`curl -L | --location`
