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
        ## Patents
        1. Object Tracking Apparatus and Method using Self‐Attention (2021)   
          <span style="color:gray"> _KR-Registration, No.10-2359982_</span>
        2. Apparatus and Method for Recognizing Heterogeneous Face Based on Relationship Between Component (2022)   
          <span style="color:gray"> _KR-Registration No.10-2356438_</span>
        3. Apparatus and Method for Tracking Pedestrians in Multiple CCTV Environment (2022)   
          <span style="color:gray"> _KR-Registration, No.10-2355006_</span>
        4. Apparatus And Method For Tracking Pedestrians In CCTV Environment (2023)   
          <span style="color:gray"> _KR-Registration, No.10-2519367_</span>
        5. Object Tracking Method and Feature Vector Extraction Method for Tracking Object (2021)   
          <span style="color:gray"> _KR-Application, No.10-2021-0165002_</span>
        6. Apparatus and Method for Detecting Anomalous Event (2020)   
          <span style="color:gray"> _KR-Application, No.10-2020-0153560_</span>
        7. Video Anomaly Detection Apparatus and Method using Relational Embedding (2022)   
          <span style="color:gray"> _KR-Application, No.10-2022-0156968_</span>
    
    design:
      columns: '1'
  - block: experience
    id: talks
    content:
      title: Experiences
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Naver Cloud (CLOVA)
          company: Research Intern
          company_logo: naver
          location: Video team
          date_start: '2023-02-01'
          date_end: '2023-08-31'
        - title: Hyundai Motor Company
          company: Research Scholarship
          company_logo: hyundai
          location: Robotics Lab.
          date_start: '2019-06-01'
          date_end: '2023-08-31'
        - title: Global Ph.D. Fellowship
          company: Research Scholarship
          company_logo: gpf
          location: National Research Foundation of Korea (NRF)
          date_start: '2019-03-01'
          date_end: '2023-08-31'
          description: |2-
              "Anomaly Detection System with Relation Embedding and Contextual Understanding in Surveillance Videos"
              (Funding KRW 150 million for 5 years)
        - title: ETRI
          company: Research Intern
          company_logo: etri
          location: Intelligent Convergence Research Lab.
          date_start: '2017-06-23'
          date_end: '2017-08-23'
        - title: Linkoping University
          company: Exchange Student
          company_logo: liu
          location: Dept. of Electrical Engineering
          date_start: '2016-09-01'
          date_end: '2017-02-28'
        - title: Kyung Hee University
          company: Undergraduate Intern
          company_logo: kh
          location: Media Lab.
          date_start: '2017-03-01'
          date_end: '2018-02-28'
          description: Development of Improving Method for Virtual View Synthesis Technology
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2020-08-25'
          description: 'Action recognition on UFC-101'
          organization: ECCV Workshop
          title: 1st Visual Inductive Priors for Data‐Efficient Deep Learning Challenge
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
