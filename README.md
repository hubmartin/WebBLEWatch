# Web BLE Watch

This is hacky proof-of-concept to use WebBLE with Infinitime to set up time and maybe other things from webpage.

# Browser

This runs only in Chrome on Win/Mac/Linux and Android. You need latest chrome with enabled experimental WebBLE functionality. Just google `chrome web ble enable`.

# Run

I use node `http-server`:

```
sudo npm i --global http-server
```

Then run in the same folder

```
http-server
```