# FoodWatch Sample

## Plugins used

`(sudo) npm install -g cordova`

`cordova plugin add cordova-plugin-whitelist`

Puis configurer config.xml avec

```
<allow-intent href="http://*/*" />
<allow-intent href="https://*/*" />
<allow-intent href="tel:*" />
<allow-intent href="sms:*" />
<allow-intent href="mailto:*" />
<allow-intent href="geo:*" />
<allow-navigation href="*" />
```



- https://github.com/apache/cordova-plugin-whitelist
- https://github.com/phonegap/phonegap-plugin-barcodescanner

# API
https://foxxy.ovh/_db/ema_api/api/docs/index.html