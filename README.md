# Stankovici Guest Wi-Fi page

## Add your QR code
Put the QR image in `assets/` and name it exactly:

`wifi-qr.png`

The page already references `assets/wifi-qr.png`. PNG is recommended. Keep the QR code square and high contrast.

## Publish with GitHub Pages
1. Create a new GitHub repository (for example `stankovici-guest-wifi`).
2. Upload `index.html` and the `assets` folder (including `wifi-qr.png` once added).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then save.
6. Wait for GitHub Pages to publish. The URL will look like:
   `https://YOUR-USERNAME.github.io/stankovici-guest-wifi/`
7. Open that URL on a phone and test both copy buttons and the QR code.
8. Use the final HTTPS URL as the URL NDEF record on your NFC tag.

## Security
This is a public static page. Anyone who knows or discovers its URL can see the Wi-Fi SSID and password. Do not use it for a network that should remain private. Consider using a guest network with client isolation.
