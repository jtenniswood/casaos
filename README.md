# Icons used for CasaOS dashboard.

Add this to your compose files
```
x-casaos:
  hostname: ${CASAHOST}
  title:
    en_us: ${CASATITLE}
  icon: ${CASAICON}
```

And this to your .env file (change the filename to match the image needed)
```
CASATITLE=Home Assistant
CASAHOST=homeassistant.tenniswoodnetwork.co.uk
CASAICON=https://github.com/jtenniswood/casaos/blob/main/Home-Assistant.png?raw=true
```
