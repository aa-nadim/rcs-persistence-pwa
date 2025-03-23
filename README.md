# PWA

`index.html` --> Open with Live Server

working-->`http://127.0.0.1:5500/index.html`

not working-->`https://127.0.0.1:5500/index.html`

## HTTPS -> `ngrok` (Temporary HTTPS Tunnel)

1. Download and install `ngrok` from `ngrok.com`.

2. ngrok config add-authtoken $YOUR_AUTH_TOKEN

3. `C:\ngrok\ngrok.exe http 5500`

4. Forwarding  `https://randomsubdomain.ngrok.io` -> `http://127.0.0.1:5500`

5. see --> `https://randomsubdomain.ngrok.io`


## Errors and warnings

1. Richer PWA Install UI won't available on desktop. Please add at least one sereenshot with the form_factor set to wide.

2. Richer PWA Install UI won't available on mobile. Please add at least one sereenshot with the form_factor is not set or set to a value other than wide.
