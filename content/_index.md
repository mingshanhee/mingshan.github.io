---
# Leave the homepage title empty to use the site title
title: Ming Shan
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: markdown
    id: news
    content:
      title: News
      text: "
        **Dec 2023**: [Award] Awarded [Singapore Data Science Consortium (SDSC) Dissertation Research Fellowship 2023](https://sdsc.sg/fellowship/) <br/>
        **Nov 2023**: [Milestone] Invited to serve as a Reviewer for [TheWebConf'24](https://www2024.thewebconf.org/) <br/>
        **Nov 2023**: [Paper Acceptance] One paper accepted at [ACM BigData'23](https://bigdataieee.org/BigData2023/) <br/>
        **Aug 2023**: [Milestone] Invited to serve as a Reviewer for [EMNLP'23](https://2023.emnlp.org/) <br/>
        **Jul 2023**: [Paper Acceptance] Three papers accepted at [ACM MM'23](https://www.acmmm2023.org/) <br/>
        **Apr 2023**: [Paper Acceptance] Two papers accepted at [IJCAI'23](https://ijcai-23.org/) <br/>
        **Mar 2023**: [Paper Acceptance] One paper accepted at [ACM MMSys'23](https://2023.acmmmsys.org/) <br/>
        **Dec 2022**: [Milestone] Passed Qualifying Preliminary Examination (QPE) ! <br/>
        **Jan 2022**: [Paper Acceptance] One paper accepted at [TheWebConf'22](https://www2022.thewebconf.org)
      "
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
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
      columns: '2'
  - block: collection
    id: publication
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
---
