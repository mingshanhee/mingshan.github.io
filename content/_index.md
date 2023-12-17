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
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '1'
  - block: markdown
    id: news
    content:
      title: News
      text: "
        **12/2023 [Tutorial Acceptance]** One tutorial accepted at [TheWebConf'24](https://www2024.thewebconf.org/)<br/>
        **12/2023 [Award]** Awarded the [Singapore Data Science Consortium (SDSC) Dissertation Research Fellowship 2023](https://sdsc.sg/fellowship/) <br/>
        **11/2023 [Milestone]** Invited to serve as a Reviewer for [TheWebConf'24](https://www2024.thewebconf.org/) <br/>
        **11/2023 [Paper Acceptance]** One paper accepted at [ACM BigData'23](https://bigdataieee.org/BigData2023/) <br/>
        **08/2023 [Milestone]** Invited to serve as a Reviewer for [EMNLP'23](https://2023.emnlp.org/) <br/>
        **07/2023 [Paper Acceptance]** Three papers accepted at [ACM MM'23](https://www.acmmm2023.org/) <br/>
        **04/2023 [Paper Acceptance]** Two papers accepted at [IJCAI'23](https://ijcai-23.org/) <br/>
        **03/2023 [Paper Acceptance]** One paper accepted at [ACM MMSys'23](https://2023.acmmmsys.org/) <br/>
        **12/2022 [Milestone]** Passed Qualifying Preliminary Examination (QPE) ! <br/>
        **01/2022 [Paper Acceptance]** One paper accepted at [TheWebConf'22](https://www2022.thewebconf.org)
      "
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
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
