# NFC Client Cards

A mobile-first collection of NFC digital business cards, hosted from one GitHub repository.

## Current card

- **INNOPRINT — Stationery & Print**
- WhatsApp, Google Maps reviews, and Instagram links are wired into the contact buttons.
- The repository root opens the INNOPRINT card.

## Adding the next client

Keep the INNOPRINT card at the root. Add every new client in its own folder:

```text
clients/
  client-name/
    index.html
    style.css
    assets/
```

This produces a dedicated GitHub Pages address such as:

```text
https://0xaaje.github.io/nfc-card/clients/client-name/
```

## GitHub Pages

In repository **Settings → Pages**, choose **Deploy from a branch**, then select the `main` branch and `/root` folder.

## Asset credits

- WhatsApp and chevron icons: Font Awesome Free 6.7.2 (CC BY 4.0 / MIT where applicable).
- Google Maps product icon: Google brand asset.
