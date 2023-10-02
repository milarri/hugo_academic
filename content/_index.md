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
  - block: features
    content:
      title: Skills
      items:
        - name: Ecology
          icon: earth-america
          icon_pack: fas
        - name: Conservation
          icon: leaf
          icon_pack: fa
        - name: R
          icon: r-project
          icon_pack: fab
        - name: Statistics
          icon: chart-line
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
        - title: Researcher
          company: CIIMAR
          company_url: 'https://www2.ciimar.up.pt/team.php?id=286'
          #company_logo: org-gc
          location: Porto (Portugal)
          date_start: '2018-10-01'
          date_end: ''
          description: Ecological impacts of invasive alien species (IAS) and the influence of climate changes on IAS. 

        - title: Postdoctoral Researcher
          company: FCT scholarship/CIIMAR
          #company_url: ''
          #company_logo: org-x
          location: Porto (Portugal)
          date_start: '2012-03-01'
          date_end: '2018-09-30'
          description: Studied the ecological impact of the Asian clam Corbicula fluminea in invaded ecosystems.
    design:
      columns: '2'
##  - block: accomplishments
  ##  content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
    ##  items:
    ##    - certificate_url: https://www.coursera.org
    ##      date_end: ''
    ##      date_start: '2021-01-25'
    ##      description: ''
    ##      organization: Coursera
    ##      organization_url: https://www.coursera.org
    ##      title: Neural Networks and Deep Learning
    ##      url: ''
    ##    - certificate_url: https://www.edx.org
    ##      date_end: ''
    ##      date_start: '2021-01-01'
    ##      description: Formulated informed blockchain models, hypotheses, and use cases.
    ##      organization: edX
    ##      organization_url: https://www.edx.org
    ##      title: Blockchain Fundamentals
    ##      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    ##    - certificate_url: https://www.datacamp.com
    ##      date_end: '2020-12-21'
    ##      date_start: '2020-07-01'
    ##      description: ''
    ##      organization: DataCamp
    ##      organization_url: https://www.datacamp.com
    ##      title: 'Object-Oriented Programming in R'
    ##      url: ''
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
 ## - block: portfolio
 ##   id: projects
 ##   content:
 ##     title: Projects
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
      columns: '2'
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
##  - block: collection
##    id: talks
##    content:
##      title: Recent Posts
##      filters:
##        folders:
##          - event
##    design:
##      columns: '2'
##      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: my-widget-123
    content:
      title: Top colaborators
      text: |-
        ## **:man_scientist: Allan Souza :finland:**

        [University of Helsinki](https://researchportal.helsinki.fi/en/persons/allan-tain%C3%A1-de-souza)   [ResearchGate](https://www.researchgate.net/profile/Allan-Souza-5)   [Website](https://allantsouza.netlify.app/)
        
        ## **:man_scientist: Ronaldo Sousa :portugal:**

        [University of Minho](https://www.uminho.pt/EN)   [ResearchGate](https://www.researchgate.net/profile/Ronaldo-Sousa)   [Website](https://sites.google.com/site/ronaldosousainvasivespecies/home)

        ## **:woman_scientist: Vanessa Modesto 🇮🇹**

        [CNR - Water Research Institute](https://www.irsa.cnr.it/wp/?page_id=807&lang=en)   [ResearchGate](https://www.researchgate.net/profile/Vanessa-Modesto-2)

        ## **:woman_scientist: Irene Martins :portugal:**

        [CIIMAR](https://www2.ciimar.up.pt/team.php?id=160)   [Twitter](https://twitter.com/ireneisamartins)   [ResearchGate](https://www.researchgate.net/profile/Irene-Martins-2)

        ## **:woman_scientist: Ester Dias :portugal:**

        [CIIMAR](https://www2.ciimar.up.pt/team.php?id=370)   [ResearchGate](https://www.researchgate.net/profile/Ester-Dias)

        ## **:woman_scientist: Marina Dolbeth :portugal:**

        [CIIMAR](https://www2.ciimar.up.pt/team.php?id=275)   [Twitter](https://twitter.com/marina_dolbeth)   [ResearchGate](https://www.researchgate.net/profile/Marina-Dolbeth)
        
        ## **:woman_scientist: Cristina Calheiros :portugal:**

        [CIIMAR](https://www2.ciimar.up.pt/team.php?id=239)   [ResearchGate](https://www.researchgate.net/profile/Cristina-Calheiros)       
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      ##subtitle:
      #text: |-
        #Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: martinailarri@gmail.com
      phone: +351 223 401 809
    ##  appointment_url: 'https://calendly.com'
      address:
        street: Terminal de Cruzeiros do Porto de Leixões, Avenida General Norton de Matos, S/N
        city: Matosinhos
        region: Porto
        postcode: '4450-208'
        country: Portugal
        country_code: Pt
      office_hours:
        - 'Every weekday from 9:30 to 17:30'
        ##- 'Wednesday 09:00 to 10:00'
      ##contact_links:
      ##  - icon: twitter
      ##    icon_pack: fab
      ##    name: DM Me
      ##    link: 'https://twitter.com/Twitter'
        ##- icon: skype
        ##  icon_pack: fab
        ##  name: Skype Me
        ##  link: 'skype:echo123?call'
        ##- icon: video
        ##  icon_pack: fas
        ##  name: Zoom Me
        ##  link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
     ## form:
     ##   provider: netlify
     ##   formspree:
     ##     id:
     ##   netlify:
          # Enable CAPTCHA challenge to reduce spam?
     ##     captcha: false
    design:
      columns: '2'
---
