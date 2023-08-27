---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-28
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: posts
    content:
      title: Research Area
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      text: |-
        Will be updated.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: compact
  - block: collection
    id: featured
    content:
      title: Featured Publications
      text: |-
        Will be updated.
    design:
      columns: '2'
      view: compact
  - block: collection
    content:
      title: Recent Publications
      text: |-
        Will be updated.
    design:
      columns: '2'
      view: compact
  - block: collection
    id: talks
    content:
      title: Professional Activities
      text: |-
        Will be updated.
    design:
      columns: '2'
      view: compact
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
