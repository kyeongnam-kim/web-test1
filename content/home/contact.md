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
  email: kn1188@knu.ac.kr
  address:
    street: 80 Daehak-ro, Bukgu
    city: Daegu
    region: 
    postcode: '41566'
    country: Republic of Korea
    country_code: KR
    contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Kyeongnam_Kim'

design:
  columns: '2'
---
