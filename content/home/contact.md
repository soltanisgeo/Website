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
  phone: +33629764989
  address:
    street: 1381 rue de la piscine
    city: Gieres
    region: Isere
    postcode: '38241'
    country: France
    country_code: FR
  coordinates:
    latitude: '45.1971'
    longitude: '5.7741'
  Contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom
      link: 'https://zoom.com'

design:
  columns: '2'
---
