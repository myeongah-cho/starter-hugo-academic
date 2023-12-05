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
  - block: collection
    id: projects
    content:
      title: Projects
      date_format: Jan 2006
      count: 0
      filters:
        folders:
          - event
    design:
      columns: '1'
      view: compact
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: portfolio
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Conferences
          tag: Conferences
        - name: Journals
          tag: Journals
    design:
      columns: '1'
      view: citation
  - block: markdown
    content:
      title: ''
      text: |-
        ### Patents
        1. Object Tracking Apparatus and Method using Self‐Attention (2021)
            <span style="color:gray"> _KR-Registration, No.10-2359982_</span>
        2. Apparatus and Method for Recognizing Heterogeneous Face Based on Relationship Between Component (2022) / _KR-Registration No.10-2356438_
        3. Apparatus and Method for Tracking Pedestrians in Multiple CCTV Environment (2022) / _KR-Registration, No.10-2355006_
        4. Apparatus And Method For Tracking Pedestrians In CCTV Environment (2023) / _KR-Registration, No.10-2519367_
        5. Object Tracking Method and Feature Vector Extraction Method for Tracking Object (2021) / _KR-Application, No.10-2021-0165002_
        6. Apparatus and Method for Detecting Anomalous Event (2020) /_KR-Application, No.10-2020-0153560_
        7. Video Anomaly Detection Apparatus and Method using Relational Embedding (2022) / _KR-Application, No.10-2022-0156968_
    
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
      text: |-
        I am always looking for talented and motivated collaborators (graduate students, postdocs, and undergraduate interns). If you're interested in joining our lab or collaborating, please email me.
      # Contact (add or remove contact options as necessary)
      email: maycho@khu.ac.kr
      phone: +82 31 201 2595
      
      address:
        street: 1732 Deogyeong-daero, Giheung-gu, Yongin-si
        city: Gyeonggi-do
        region: Republic of Korea
      directions: Room 7032, Woojungwon Building, Kyung Hee University
      coordinates:
        latitude: '37.2458680'
        longitude: '127.0772930' 
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
