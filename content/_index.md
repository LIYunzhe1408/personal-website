---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: ENGINEER ROBOT IN RMUC 2023
          content: Manipulating to exchange Minerals
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: engineer.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#666'
          link:
            icon: video
            icon_pack: fas
            text: Learn More
            url: https://youtu.be/qeRvdmcNFAc
        - title: INSPIRE AWARD
          content: The most cherishable period during my career in #1408 Facing the Giants
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: SAS.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
          link:
            icon: video
            icon_pack: fas
            text: Learn More
            url: https://youtu.be/ZKn0rDUpNfY
        - title: MY THREE-YEAR SRM JOURNEY
          content: Winning 3rd Place & Standing on the podium for the first time 
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: RMUL.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
          link:
            icon: video
            icon_pack: fas
            text: Learn More
            url: https://youtu.be/ZKn0rDUpNfY
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

  - block: about.biography
    id: about
    content:
      title: Jonas
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: python
          description: 
          icon: python
          icon_pack: fab
        - name: java
          description: 
          icon: java
          icon_pack: fab
        - name: deep-learning
          description: 
          icon: deep-learning
          icon_pack: custom
        - name: leadership
          description: 
          icon: leadership
          icon_pack: custom
        - name: project management
          description: 
          icon: project-management
          icon_pack: custom
        - name: linear algebra
          description: 
          icon: mathematic
          icon_pack: custom
        - name: C++
          description: 
          icon: c-
          icon_pack: custom
        - name: entrepreneurship
          description: 
          icon: entrepreneurship
          icon_pack: custom
        - name: Crafting
          description: 
          icon: repair
          icon_pack: custom

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Team Leader & Chief Technician
          company: SRM
          company_url: ''
          company_logo: srm
          location: Shanghai University
          date_start: '2020-09-01'
          date_end: ''
          description: |2-
              Responsibilities include:
              * Project Management
              * Seek funding and operate the whole team          
              * Develop algorithms to activate Energy Rune in the competition
              

        - title: Algorithm Engineer Intern
          company: ByteDance
          company_url: 'https://www.bytedance.com/en/'
          company_logo: bytedance
          location: Kaide Shangpu Business Center, No.99, Jiangwancheng Road, Yangpu District, Shanghai
          date_start: '2023-09-01'
          date_end: '2023-06-28'
          description:  |2-
              Responsibilities include:
              * Collect and pre-process users’ behavioral data from the established platform
              * Fine-tune established models to extract key information and construct Knowledge Graph
              * Collaborate with software engineers to build enterprise-level platform with models
              * Analyze the positive impact of the model landing on the e-commerce ecosystem

        - title: Research Assistant
          company: Shanghai University Machine Learning Lab
          company_url: ''
          company_logo: ML
          location: Shanghai University
          date_start: '2021-09-01'
          date_end: '2023-05-01'
          description:  |2-
              Responsibilities include:
              * Collect and Pre-process literature data on NASICON
              * Train and fine-tune NER&RE models
              * Build a knowledge platform

        - title: Algorithm Engineer Intern
          company: SHANGHAI-FANUC Robotics CO., LTD.
          company_url: 'https://www.shanghai-fanuc.com.cn/'
          company_logo: shanghai-fanuc
          location: NO 1500, Fulian Road, Baoshan District, Shanghai
          date_start: '2021-09-04'
          date_end: '2021-06-30'
          description:  |2-
              Responsibilities include:
              * Integrate concept of rigid body motion and the robot with Eigen library in C++
              * Develop algorithms to detect screws, holes to inspect automotive engine assembly results
              * Optimize detection performance with Least Squares

        - title: Team Leader & Chief Programmer
          company: F.G.(Facing The Giants)
          company_url: ''
          company_logo: fg
          location: Shanghai Xinzhuang Senior High School
          date_start: '2017-09-01'
          date_end: '2020-08-01'
          description:  |2-
              Responsibilities include:
              * Assign workloads and manage the process
              * Liaise with other teams
              * Develop controlling and vision algorithms
              * Assist build the robot structure 
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Highlights'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://youtu.be/qeRvdmcNFAc
          date_end: ''
          date_start: '2023-06-04'
          description: Manipulator and manager of Engineer Robot
          organization: RoboMaster
          organization_url: https://www.robomaster.com/en-US
          title: Engineer Robot of SRM
          url: 'https://youtu.be/qeRvdmcNFAc'
        - certificate_url: https://youtu.be/REICVFIxuHA
          date_end: ''
          date_start: '2020-09-01'
          description: From rookie to team leader of SRM in three years.
          organization: SRM
          organization_url:
          title: My three-year journey as a SRMer
          url: https://youtu.be/REICVFIxuHA
        - certificate_url: https://youtu.be/ZKn0rDUpNfY
          date_end: '2020-08-01'
          date_start: '2017-09-01'
          description: Team Leader of Facing The Giants
          organization: FIRST®
          organization_url: https://www.firstinspires.org/
          title: Inspiration | FIRST® Tech Challenge Documentary
          url: 'https://youtu.be/ZKn0rDUpNfY'
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Highlights
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
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
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
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
