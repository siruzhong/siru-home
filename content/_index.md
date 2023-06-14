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
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
  - block: experience
    id: works
    content:
      title: 💻 Work Experience
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
          company: HKUST(GZ)
          company_url: "https://hkust-gz.edu.cn/"
          company_logo: hkust(gz)
          location: GuangZhou
          date_start: "2023-05-01"
          date_end: ""
          description: |2-
              **Responsibilities include**:
              * Under the guidance of Professor Liang Yuxuan **[yuxuanliang.com](http://yuxuanliang.com/)**, the main research areas include spatiotemporal data science, spatiotemporal artificial intelligence, urban computing, intelligent transportation, etc.
              * Independently built the laboratory portal website, which includes major modules such as the homepage, publications, achievements, news, and contact us. The website can be found at 111.230.109.230 and is gradually being perfected.
              * Deeply involved in the TKDE journal submission project related to air quality prediction, independently responsible for the construction of the visualization platform, improving the visualization effect of research data and research efficiency.
        - title: Backend Development Engineer
          company: Tencent(SZ)
          company_url: "https://www.tencent.com/zh-cn"
          company_logo: tencent
          location: Shenzhen
          date_start: "2022-07-04"
          date_end: "2023-05-01"
          description: |2-
              **Fiber Team Compliance Bus Group**
              - Fiber is an orchestration management system based on IFTTT and event-driven principles. It is used to integrate online tools and interweave them to interact with each other, aiming to reduce the overall orchestration cost of the work process.
              - Independently responsible for designing and developing the DSL related to business processes, it was successfully implemented in various business lines (including QQ, News, Video, and App Treasure), significantly improving the overall efficiency of the workflow.
              - In conjunction with the frequent change operation and maintenance scenarios of the TEG cloud architecture platform department, it participated in the design of a unified compliance event bus and event model management that can connect all online operation and maintenance components.
              - Responsible for the basic capabilities and management end capabilities of the event bus, established the standardization process of CI/CD events, provided the definition and legality verification capability of the event schema, and integrated it into the visual management of the management end, helping to establish a standardized data system to achieve advanced DevOps.
              - Responsible for the implementation of the event bus data reporting capability and observability, the full-link statistics and alert capabilities of event data were achieved through Prometheus + Grafana.

              **Cloud IDE Team Container Research and Development Group**
              - Codespaces is a cloud-based R&D collaboration platform that is cloud-native and code-centric. It caters to software engineers and comes pre-loaded with a variety of out-of-the-box integrated development environments on the cloud, allowing development anywhere, anytime, without the need to install or configure the environment.
              - Responsible for the maintenance and optimization of R&D container Agents, which are used to provide capability support for file, process, network, and other related requirements within the container runtime.
              - Responsible for the multi-container architecture modification of the container base, successfully separating resource usage, significantly improving user experience, guaranteeing elastic resource utilization, and ensuring smooth development.
              - Responsible for the access of the VSCode client, providing remote development capabilities, and completing the corresponding container Agent and IDE plugin implementation.
        - title: Summer Intern
          company: Tencent(BJ)
          company_url: "https://www.tencent.com/zh-cn"
          company_logo: tencent
          location: Beijing
          date_start: "2021-06-25"
          date_end: "2021-09-08"
          description: |2-
              **Social Background Efficiency Tool Group**
              - QQCD is a service deployment platform for the QQ team. It unifies multiple underlying cloud platforms within the company, abstracts the underlying deployment resources, supports related deployment across multiple platforms, manual/automatic deployment orchestration modes, and provides clear deployment views and process control, improving the deployment efficiency of the business.
              - Responsible for the daily development and maintenance of the QQCD platform. Common error scenarios were refactored and optimized, effectively improving the stability of platform service deployments, significantly reducing the online bug rate, and improving business deployment efficiency.
              - Responsible for the maintenance and reconstruction of QQ's quality management platform. The outdated HTTP interface was transformed into an RPC form, and the code structure and quality were optimized. Grayscale updates, deployment, and launch were carried out.
              - Passed the internship assessment with a code rating of "A". During the internship, the code output was 11.2k. Finally, received a special offer.
    design:
      columns: "1"
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: "Accomplish&shy;ments"
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-040723.png
          date_end: ""
          date_start: "2023-01"
          description: ""
          organization: Tencent
          organization_url: https://www.tencent.com/zh-cn
          title: Tencent iCode Certification
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-040905.png
          date_end: ""
          date_start: "2022-09"
          description: ""
          organization: Tencent
          organization_url: https://www.tencent.com/zh-cn
          title: Tencent Code World Program Silver Award
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-040728.jpg
          date_end: ""
          date_start: "2020-07"
          description: ""
          organization: Tencent
          organization_url: https://www.tencent.com/zh-cn
          title: Tencent Graduates Training Outstanding Student
          url: ""
    design:
      columns: "2"
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ""
      text: ""
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
      columns: "2"
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
          tag: "*"
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: "1"
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ""
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: "1"
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: "2"
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
      columns: "2"
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: "2"
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: "2"
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        You can send an email to me or add me on wechat!
      # Contact (add or remove contact options as necessary)
      email: bareth@qq.com
      contact_links:
        - icon: weixin
          icon_pack: fab
          name: Discuss on wechat
          link: "https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-032135.png"
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: "2"
---
