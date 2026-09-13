# NFC Client Cards

A mobile-first collection of NFC digital business cards hosted from one GitHub repository. The root page is a small directory, and each client has an isolated page and asset folder.

## Repository structure

```text
nfc-card/
  index.html
  style.css
  assets/
  clients/
    innoprint/
      index.html
      assets/
    client-name/
      index.html
      assets/
```

## Current client

**INNOPRINT — Stationery & Print** is the first client:

```text
https://0xaaje.github.io/nfc-card/clients/innoprint/
```

Its WhatsApp, Google Maps reviews, and Instagram buttons are wired to the client links. The card uses the shared root `style.css`; its own images and icons stay inside `clients/innoprint/assets/`.

## Adding a new client

1. Copy `clients/innoprint/` to `clients/client-name/`.
2. Replace the brand image and icons in that client's `assets/` folder.
3. Update the text and contact URLs in its `index.html`.
4. Add the new client to the root `index.html` directory list.

Every client then gets a dedicated GitHub Pages address:

```text
https://0xaaje.github.io/nfc-card/clients/client-name/
```

## GitHub Pages

In repository **Settings → Pages**, choose **Deploy from a branch**, then select the `main` branch and `/root` folder.

## Asset credits

- WhatsApp, Instagram, contactless, and chevron icons: Font Awesome Free 6.7.2 (CC BY 4.0 / MIT where applicable).
- Google Maps product icon: Google brand asset.
