# polkadot-node
Polkadot node - Gitcoin challenge

I have created a Polkadot node on a VPS droplet from digitalocean 8gb-160SSD Ubuntu 18.04 LTS Server.

After installation, I have made a script to make the node run polkadot validator node as systemd service since I'm running it on a remote server (to be able to disconnect my ssh connection while keeping the node service running) following the guide from <a href='https://wiki.polkadot.network/docs/en/maintain-guides-how-to-systemd'>wiki.Polkadot</a> with some edits to the code in the guide.

See the script code at Polka-node.sh
See the systemd .service file at Polka-Validator.service
See node screenshot at appitize-node.png
