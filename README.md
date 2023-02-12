# Repo of three key files for easy Synapse hosting
I put notes within the files to explain what's happening. Hopefully it is easy to follow. Caddy takes care of automatic https certificates and has a less painful experience for set up than nginx or apache instructions in the Synapse documents. ddclient is a foss package you can use for pinging your domain name registrar when your IP address is cycled by your ISP, or VPS hoster. A + DNS Records are edited in your registrar's DNS files. You can find guides in their documents on how to use A + DNS records. Essentially you're assigning prefixes to your website URL. Also your "@" record is the first established connection and everything builds off that. I could have some theory wrong, but it works on my machine.

## Intention
Synapse has a better experience than XMPP. It's usually more work to get Matrix started when you're a beginner, so these files will get your feet wet. I find the YT videos suck on setting things up, and having concise notes within config files is a better way to learn. Minimal, high-yield instructions are better because you get to plug and play while you read. I think tutorials are better than passively watching videos, so hopefully a successful first attempt will attract more people interested to sys admin their own servers.

### Synapse Admin Docs
https://matrix-org.github.io/synapse/latest/usage/configuration/config_documentation.html

### Synapse Admin GUI 

https://github.com/Awesome-Technologies/synapse-admin/blob/master/docker-compose.yml

Awesome-Selfhosted is also a useful repo for beginner sys admins.

# Contents
1) Caddy v2 Configuration for Synapse: 

a) .wellknown 

b) Reverse Proxy

c) Static Website directory pathing


2) ddclient configuration for Synapse


3) Synapse homeserverl.yaml configuration file
