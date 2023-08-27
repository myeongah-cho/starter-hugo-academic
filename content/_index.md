---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    id: posts
    content:
      title: Will be uploaded
      subtitle: ''
    design:
      columns: '1'
  - block: markdown
    id: projects
    content:
      title: Will be uploaded
      subtitle: ''
    design:
      columns: '1'
  - block: markdown
    id: featured
    content:
      title: Will be uploaded
      subtitle: ''
    design:
      columns: '1'
  - block: markdown
    id: talks
    content:
      title: Will be uploaded
      subtitle: ''
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
        # Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: maycho0305@gmail.com
      phone: +82 2 2123 7843
      # appointment_url: 'https://calendly.com'
      address:
        street: Yonsei University
        city: Seoul
        region: Republic of Korea
      directions: C507, Engineering Building, Department of Electrical and Electronic Engineering
      office_hours:
        - 'Monday 9:00 to Friday 18:00'
      contact_links:
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://us04web.zoom.us/j/9154272063?pwd=ZmpIaFBRa0pDYjJLcFAyQmZWNjl1UT09'
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
    design:
      columns: '2'
---
