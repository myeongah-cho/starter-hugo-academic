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
  - block: portfolio
    id: projects
    content:
      title: Featured Publications
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Conference
          tag: Conference
        - name: Journal
          tag: Journal
    design:
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
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
      text: |-
        I am always looking for talented and motivated collaborators (graduate students, postdocs, and undergraduate interns). If you're interested in joining our lab or collaborating, please email me.
      # Contact (add or remove contact options as necessary)
      email: maycho@khu.ac.kr
      phone: +82 31 201 2595
      appointment_url: [Aladdin (for KHU)](https://aladdin.khu.ac.kr/)
      address:
        street: 1732 Deogyeong-daero, Giheung-gu, Yongin-si
        city: Gyeonggi-do, 17104
        region: Republic of Korea
      directions: Room 7032, Woojungwon Building, Kyung Hee University
      contact_links:
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://khu-ac.zoom.us/j/5962979679'
      # Automatically link email and phone or display as text?
      autolink: true
     
    design:
      columns: '2'
---
