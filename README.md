# tesla.jackmd.com

GitHub Pages host for the public key of Jack's Tesla Fleet API application (Home Assistant, 213SCC).

- Tesla reads the key at `https://tesla.jackmd.com/.well-known/appspecific/com.tesla.3p.public-key.pem`.
- The key is a PUBLIC key. The private key stays in Home Assistant on netpi and never comes here.
- `.nojekyll` must stay: without it, Jekyll drops the `.well-known` folder.
- Other content can live here; keep that one path.
