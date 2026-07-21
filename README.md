# WeLayer GTM Community Template

Official Google Tag Manager Community Template for WeLayer.

The template collects standardized website events and sends them to the WeLayer platform with privacy-first consent management, automatic identity handling, and reliable server-side delivery.

## Features

- Google Tag Manager Community Template
- Automatic event collection
- Privacy-first consent handling
- Identity management
- Standardized event schema
- Server-side delivery
- Easy installation
- Versioned releases

## Requirements

- Google Tag Manager Web Container
- WeLayer account
- WeLayer Tracking endpoint

## Installation

1. Open your GTM container.
2. Go to **Templates**.
3. Open the **Community Template Gallery**.
4. Search for **WeLayer**.
5. Add the template.
6. Create a new tag using the template.
7. Configure your WeLayer settings.
8. Publish your container.

A detailed guide is available in:

- [Installation Guide](docs/installation.md)

## Supported Events

The template supports standardized website events, including:

- page_view
- view_item
- view_item_list
- select_item
- add_to_cart
- remove_from_cart
- begin_checkout
- purchase
- login
- sign_up
- search
- generate_lead
- custom events

Complete documentation:

- [Supported Events](docs/events.md)

## Permissions

The template only requests the permissions required to:

- Read Event Data
- Read Consent State
- Access Cookies (when configured)
- Send HTTP requests to the configured WeLayer endpoint

## Repository Structure

```
template.tpl
metadata.yaml
README.md
CHANGELOG.md
LICENSE
docs/
images/
```

## Documentation

- Installation Guide
- Event Reference
- Release Notes

## License

Apache License 2.0

## Support

GitHub Issues

https://github.com/welayer/welayer-gtm-template/issues

## Changelog

See:

CHANGELOG.md
