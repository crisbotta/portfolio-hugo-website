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
  email: test@example.org
  phone: +353 83 2005728
  address:
    #street: 450 Serra Mall
    city: Dublin
    #region: CA
    #postcode: '94305'
    country: Ireland
    country_code: IE
  #coordinates:
   #latitude: '37.4275'
    #longitude: '-122.1697'
  #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: mastodon
      icon_pack: fab
      name: DM Me
      link: 'https://crisbotta@mastodon.social'
    - icon: likendin
      icon_pack: fas
      name: DM Me
      link: 'https://linkedin.com/in/crisbotta'

design:
  columns: '2'
---
