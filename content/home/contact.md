---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: saeed.soltani@univ-grenoble-alpes.fr
  phone: +330629764989
  address:   
    street: 1381 Rue de la Piscine
    city: Gières
    region: CA
    postcode: '38610'
    country: France
    country_code: Fr
design:
  columns: '2'
---
