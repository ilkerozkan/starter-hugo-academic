---
# Leave the homepage title empty to use the site title
title: Assoc.Prof.Dr.
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 # - block: experience
#    content:
 #     title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
 #     date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
   
#   - title: Professor of Semiconductor Physics
#      company: University X
   #       company_url: ''
  #        company_logo: org-x
 #         location: California
#          date_start: '2016-01-01'
#         date_end: '2020-12-31'
#          description: Taught electronic engineering and researched semiconductor physics.
#    design:
#      columns: '2'
 

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
      subtitle: Assoc.Prof.Dr. Ilker Ali OZKAN
      text: |-
 #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: ilkerozkan@selcuk.edu.tr
      phone: +90 332 223 33 92
      appointment_url: 'https://calendly.com'
      address:
        street: Alaaddin Keykubad Campus, Faculty of Technology
        city: Konya
        region: TR
        postcode: '42030'
        country: Türkiye
        country_code: TR
      directions: Enter Building A and take the stairs to Office 407 on Floor 4
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
 #       - icon: twitter
 #         icon_pack: fab
 #         name: DM Me
 #         link: 'https://twitter.com/Twitter'
 #       - icon: skype
 #         icon_pack: fab
 #         name: Skype Me
 #         link: 'skype:echo123?call'
 #       - icon: video
 #         icon_pack: fas
 #         name: Zoom Me
 #         link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
