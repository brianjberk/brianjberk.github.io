# brianjberk.github.io

Hosts the public key for my Tesla Fleet API application, used by Home Assistant:

https://brianjberk.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem

`.nojekyll` makes GitHub Pages serve the `.well-known` directory. The matching
private key never leaves the Home Assistant server. If that key is ever
replaced, update the `.pem` file here before re-registering with Tesla.
