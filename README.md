# Web BLE Watch

This is hacky proof-of-concept to use WebBLE with Infinitime to set up time and maybe other things from webpage.

Working example and more info is on GitPages here https://hubmartin.github.io/WebBLEWatch/

Video of using https://www.youtube.com/watch?v=IakiuhVDdrY

# Browser

This runs only in a Chromium-based browser (such as Chrome or Edge) on Win/Mac/Linux and Android. You need latest chrome with enabled experimental WebBLE functionality. Just google `chrome web ble enable`.

# Run

I use node `http-server`:

```
sudo npm i --global http-server
```

Then run in the same folder

```
http-server
```

If you run it local, you have to use `localhost`, in the internet you need `https`. This is mandatory, google has decided.