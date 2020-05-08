# dom-tunnel


dom-tunnel exposes your local ais-dom gate to the world for easy Internet access!
## installation ##

```
npm install -g dom-tunnel
```

This will install the localtunnel module globally and add the 'lt' client cli tool to your PATH (/data/data/pl.sviete.dom/files/usr/bin/env on gate)

```
yarn add localtunnel
```

## CLI usage

When localtunnel is installed globally, just use the `lt` command to start the tunnel.

```
lt --port 8000
```

Thats it! It will connect to the tunnel server, setup the tunnel, and tell you what url to use for your testing. This url will remain active for the duration of your session.


## License

MIT
