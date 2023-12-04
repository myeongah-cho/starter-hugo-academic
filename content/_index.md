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
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Projects
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: '2022-06-01'
          date_start: '2021-06-01'
          description: 3D View Generation, Depth Estimation, 2D-3D Retrieval, 3D Object Detection
          icon: edx
          organization: LG Electronics
          title: 2D-3D Feature Correspondence Learning for Virtual Scene Reconstruction
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: edx
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '1'
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
