# Mayer Haath Jewellery Store

A responsive single-page jewellery storefront built for a Kolkata-based handmade jewellery business.

## Features

- Responsive product catalogue and mobile-first layout
- Persistent floating shopping-bag access after adding an item
- Cart totals, removal, and checkout validation
- Separate country-code and phone-number fields
- UPI deep-link payment flow
- Automatically generated WhatsApp order bill
- Cash-on-delivery and UPI payment options
- Accessible labels, keyboard-friendly drawer, and reduced-motion support

## Run locally

Open `index.html` in a browser or serve the directory with any static web server.

## Store configuration

The public repository intentionally contains demo contact and payment values. For a private deployment, replace the values in `STORE_CONFIG` inside `index.html`:

```js
const STORE_CONFIG = {
  whatsappNumber: '910000000000',
  upiId: 'demo@upi',
  upiPayee: 'Mayer Haath Jewellery'
};
```

Do not commit personal phone numbers or payment identifiers to a public repository.

## Status

Working portfolio version. The production business deployment uses private merchant configuration.

## Author

Adrij Ghosh

