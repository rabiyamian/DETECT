---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 55


title: "**Contact Us**"
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
  email: Michael.B.Cannell@uth.tmc.edu
  phone: 972-546-2925
  address:
    street: 2777 N Stemmons Fwy, Suite 8400
    city: Dallas
    region: TX
    postcode: '75207'
    country: United States
    country_code: US
#  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
#  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/brad_cannell'
    - icon: linkedin
      icon_pack: fab
      name: Connect
      link: 'https://www.linkedin.com/in/bradcannell/'
    - icon: facebook
      icon_pack: fab
      name: Message Me
      link: 'https://www.facebook.com/Brad-Cannell-PhD-MPH-109345984850672'
#    - icon: video
#      icon_pack: fas
#      name: Zoom Me
#      link: 'https://zoom.com'

design:
  columns: '2'

# Activate this widget? true/false
active: true

---
<center>

{{< figure src="detect_logo.jpg" caption="" numbered="false" >}}
