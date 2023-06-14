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
          date_start: "2023-01-01"
          description: |2-
              This certification signifies the successful completion of the comprehensive methodology training in DevOps, Testing, Quality Build-in, Efficient Collaboration, and Efficient Operations. Furthermore, it demonstrates the achievement of passing all theoretical and practical assessments of the Engineering Literacy Improvement Program for PCG R&D personn
          organization: Tencent
          organization_url: https://www.tencent.com/zh-cn
          title: Tencent iCode Certification
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-040905.png
          date_end: ""
          date_start: "2022-09-01"
          description: |2-
              The CodeWorld project, which was a part of Tencent PCG's graduate training program, provided an opportunity for interdisciplinary teams to collaborate and deliver practical projects within a month. As a key member of the team, my responsibilities revolved around database design, formulation of comprehensive API documentation for both front-end and back-end, as well as contributing to the development of essential backend database services.
              
              Our team successfully developed a ToG nucleic acid detection reminder assistant as our project, aimed at assisting individuals impacted by invalid test results in planning their travels. This assistant utilized predictive analysis to estimate future test times, cross-checked regional policies, and set timely reminders for the users.
              
              In recognition of our accomplishments, our team was honored with the silver award, securing the second position among twelve competing teams.
          organization: Tencent
          organization_url: https://www.tencent.com/zh-cn
          title: Tencent Code World Program Silver Award
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-040728.jpg
          date_end: ""
          date_start: "2022-07-01"
          description: |2-
              Tencent's annual new employee Training program serves as a valuable platform that brings together individuals from diverse positions and major business groups. The program aims to seamlessly integrate recent graduates into the company's dynamic environment, fostering collaboration and camaraderie through various group activities. Despite being the youngest participant, I had the privilege of taking on the role of group leader, entrusted with important responsibilities such as managing course attendance, organizing after-school activities, evaluating team performance, planning the graduation party, and more.
              
              Guiding a team of seven talented individuals, we dedicated ourselves to completing all assigned projects within a challenging five-day timeframe. Through our collective efforts, we achieved exceptional outcomes, which led to my recognition as an Excellent Student (ranked 6th out of 50).
              
              My experience as a group leader allowed me to demonstrate my strong organizational acumen, effective communication skills, and the ability to motivate and inspire team members. By coordinating our efforts and providing guidance, we achieved remarkable results. This honor as an Excellent Student is a testament to my commitment, leadership abilities, and significant contributions to the team's success during the training program.
          organization: Tencent
          organization_url: https://www.tencent.com/zh-cn
          title: Tencent Graduates Training Outstanding Student
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-041954.jpg
          date_end: ""
          date_start: "2022-06-01"
          description: |2-
              The Excellent Graduation Design Award, presented by the Department of Computer and Information Technology at Hefei University of Technology, is a prestigious accolade that acknowledges exceptional achievements in the field. I am deeply honored to have been bestowed with this prestigious award in recognition of my significant contributions during my tenure as a student in the Internet of Things engineering program.
              
              During the program, I undertook the challenge of conceptualizing and developing a groundbreaking digital resource sharing platform. This platform represents a paradigm shift in information resource management and organization, effectively addressing the prevalent issue of information overload. By serving as a comprehensive hub for high-quality resources, it enables seamless sharing and utilization while ensuring the filtration of subpar content. Through its precision in granting access to premium resources, it significantly enhances individual resource acquisition efficiency, thus fostering productivity in learning and innovation.
              
              The journey I embarked upon was marked by my successful navigation through two rigorous rounds of screening, ultimately culminating in my participation in the defense and evaluation of graduation design projects at both the departmental and university levels. The recognition and accolades bestowed upon me by the esteemed judging panel further affirm the significance and excellence of my project. It is truly humbling to be one of the select few, as the Excellent Graduation Design Award is granted to only two outstanding students among a cohort of 100.
          organization: HFUT
          organization_url: http://www.hfut.edu.cn/
          title: HFUT Outstanding undergraduate Graduation Project
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-074554.jpg
          date_end: ""
          date_start: "2021-05-01"
          description: |2-
              The National English Competition for College Students (NECCS) is widely recognized as the most comprehensive and inclusive nationwide competition in China, dedicated to evaluating the comprehensive English abilities of college students. It is a source of great pride for me to have achieved the distinguished honor of winning the third prize in this prestigious competition.
              
              Participating in NECCS was truly transformative, enabling me to make significant strides in improving my English proficiency across various areas such as reading, writing, listening, and more. This invaluable experience has provided me with a strong foundation to pursue further growth in my English studies and future endeavors.
          organization: TEFL China
          organization_url: http://www.chinaneccs.cn/
          title: National English Competition for College Students Third Prize
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-074858.jpg
          date_end: ""
          date_start: "2020-10-01"
          description: |2-
              The CSDN "GEEK+" Technical Original Blogger Contest is a highly esteemed nationwide competition that attracts participants from around the world, including talented bloggers within the CSDN community. It serves as a platform to recognize and celebrate outstanding bloggers who excel in creating technical content. The evaluation process encompasses various criteria, such as the number of original articles, readership, engagement metrics, account activity, and the depth of technical expertise demonstrated in the work.
              
              I am deeply honored to have been selected as one of the top 30 bloggers and awarded the first prize in this prestigious contest. This achievement speaks to my unwavering dedication to delivering high-quality content and engaging with a diverse readership. It fuels my motivation to continue sharing valuable insights and making meaningful contributions to the wider technical community. This national recognition further reinforces my commitment to continuous improvement and inspires me to strive for excellence in all my blogging endeavors.
              
              I am delighted to share that my CSDN blog has experienced remarkable growth and success. With over 30,000 dedicated followers, I am grateful for their continued support, which attests to the value and relevance of the content I provide. Furthermore, the significant number of visits, totaling an impressive 870,000, is a testament to the widespread impact of my articles. The fact that my work has been favorited over 20,000 times signifies the appreciation and recognition it has garnered from readers.
              
              These accomplishments encourage me to push the boundaries of my knowledge and expertise, delivering even more valuable and insightful content. I remain committed to engaging with the CSDN community and contributing to its vibrant ecosystem of technical knowledge-sharing.
          organization: CSDN
          organization_url: https://www.csdn.net/
          title: First prize of CSDN "GEEK+" technical original Blogger Contest
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-075202.jpg
          date_end: ""
          date_start: "2020-08-01"
          description: |2-
              The HFUT Robot Competition featured a challenging 2D Project Team event, in which I actively participated. The competition revolved around utilizing the soccerServer platform, designed for Linux, and involved developing a team capable of playing soccer. Our objective was to enhance the provided C++ code, which initially only allowed for kicking in a single direction, by incorporating advanced techniques and strategies.
              
              In the competition, I focused on expanding the codebase and implementing various kicking techniques, refining the strength and angle of passes and shots, and devising player strategies based on different positions. Through collaborative efforts and countless hours of dedication, our team successfully transformed the basic team into a formidable force ready to compete against other teams.
              
              I am thrilled to share that our hard work and innovation paid off, as our team was awarded the Second Prize in the competition. This recognition is a testament to our collective effort and highlights the progress we made in advancing our skills in robotics and gameplay strategy. It was a fulfilling experience that not only deepened my understanding of the field but also fostered teamwork and problem-solving abilities.
          organization: HFUT
          organization_url: http://www.hfut.edu.cn/
          title: HFUT Robot Competition 2D Project Team Second Prize
          url: ""
        - certificate_url: https://siruzhong-1305674339.cos.ap-hongkong.myqcloud.com/2023-06-14-075340.png
          date_end: ""
          date_start: "2020-08-01"
          description: |2-
              Throughout my four years at Hefei University of Technology, I have been fortunate to receive the Progress Scholarship twice and the Third-class Scholarship once. These awards recognize my continuous academic improvement and growth. From my first year to my final year, I have consistently strived to enhance my academic performance.
              
              I am proud to share that I ranked 18th out of 100 students in my major, highlighting my dedication and hard work in achieving academic excellence. This accomplishment is a testament to my perseverance, commitment to self-improvement, and relentless pursuit of knowledge.
              
              I am grateful for the opportunities and support provided by Hefei University of Technology, as well as the recognition bestowed upon me through these scholarships. They serve as a reminder that hard work, determination, and a growth mindset are essential factors in achieving success.
          organization: HFUT
          organization_url: http://www.hfut.edu.cn/
          title: Hefei University of Technology Scholarship
          url: ""
    design:
      columns: "1"
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
