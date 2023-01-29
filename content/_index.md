---
# Leave the homepage title empty to use the site title
title: Francisco Espinoza
date: 2022-10-24
type: landing

sections:
  design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Comparative Politics
          description: 
          icon: person-sign
          icon_pack: fas
        - name: Quantitative methods
          description: 
          icon: chart-line
          icon_pack: fas
        - name: Social research
          description: 
          icon: 
          icon_pack: fas
        - name: Social stratification
          icon: scale-unbalanced-flip
          icon_pack: fas
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
        - title: Research Assistant
          company: The University of Manchester
          company_url: ''
          company_logo: 
          location: Manchester, UK
          date_start: '2018-05-01'
          date_end: ''
          description:
              Development of multilingual data collection platform for longitudinal research project among young people in the UK.            
        - title: Professional
          company: Municipality of Santiago
          company_url: ''
          company_logo: org-x
          location: Santiago, Chile
          date_start: '2015-03-01'
          date_end: '2017-12-31'
          description: Design, implementation and evaluation of innovative evidence-based social policies.
    design:
      columns: '2'
  - block: Education
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Education'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.manchester.ac.uk
          date_end: ''
          date_start: '2020-09-25'
          description: ''
          organization: The University of Manchester
          organization_url: https://www.manchester.ac.uk
          title: PhD student in Politics
          url: ''
        - certificate_url: https://gobierno.uchile.cl/
          date_end: '2016-12-31'
          date_start: ''
          description: 
          organization: University of Chile
          organization_url: https://gobierno.uchile.cl/
          title: Master in Political Sciente
          - certificate_url: https://facso.uchile.cl/
          date_end: '2013-03-01'
          date_start: ''
          description: ''
          organization: University of Chile
          organization_url: https://facso.uchile.cl/
          title: Sociologist, Licentiate degree in Sociology, 
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
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
  #- block: contact
  #  id: contact
  #  content:
  #    title: Contact
  #    subtitle:
  #    text: |-
  #      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      #email: francisco.espinoza@manches
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      #address:
      #  street: 450 Serra Mall
      #  city: Stanford
      #  region: CA
      #  postcode: '94305'
      #  country: United States
      #  country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
     # contact_links:
     #   - icon: twitter
     #     icon_pack: fab
     #     name: DM Me
     #     link: 'https://twitter.com/fcoespin_'
        #- icon: skype
        #  icon_pack: fab
        #  name: Skype Me
        #  link: 'skype:echo123?call'
        #- icon: video
        #  icon_pack: fas
        #  name: Zoom Me
        #  link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: false
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
        #  captcha: false
    #design:
    #  columns: '2'
---
