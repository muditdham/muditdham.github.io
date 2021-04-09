---
layout: home
header:
  title: Hi there, I'm Mudit Dham
  text: 
    Trying to Listen when Data talks
  action: # action button is optional
    label: Find Out More
    url: '#about'


sections:
  - type: about.html
    section_id: about
    background_style: bg-primary
    title: Data Scientist | ML Developer
    texts: 
      - Graduate student passionate about solving problems using data and trying to draw actionable insights that help businesses make key decisions and create impact. 
      - Leveraging both my academic knowledge and professional learnings, I am able to efficiently build and evaluate Machine Learning and Deep Learning models. 
      - I now aspire to be part of a team, with like-minded technology enthusiasts and data science practitioners striving to take on challenges of this rapidly evolving domain of Artificial Intelligence. 
      - I strongly believe that with Big Data comes Big responsibility and it has the power to make world a better place.
    quote: "Always trying to find the needle in a haystack"
    actions:
      - title: Skills
        # url: '#page-top'
        url: '#skills'
        class: btn-dark

  # - type: services.html
  - type: skills.html
    section_id: skills
    # background_style: bg-info
    title: Technical Skills
    services:
      # - title: Sturdy Templates
      #   text: Our templates are updated regularly so they don't break.
      #   icon: fa-gem text-info
      #   url: https://startbootstrap.com/
      - title: Programming 
        text: Python, Java, Julia
        icon: fa-code
      - title: Database
        text: MySQL, MSSQL, NoSQL
        icon: fa-database
      - title: Machine Learning
        text: Scikit-Learn, XGBoost, H20.ai, Weka
        icon: fa-laptop-code
      - title: Deep Learning
        text: Keras, Tensorflow, PyTorch
        icon: fa-robot
      - title: BI & Dashboard
        text: Tableau, PowerBI, TIBCO Spotfire, Dundas
        icon: fa-chart-line
      - title: Big Data and Cloud
        text: Apache Spark, Azure ML
        icon: fa-cloud
    
    actions:
      - title: Work Experience
        url: '#workex'
        class: btn-dark
        
  # - type: timeline.html
  - type: workex.html
    section_id: workex
    title: Work Experience
    background_style: bg-dark text-primary
    last_image: assets/img/logos/education.png
    roles:
      - image: assets/img/logos/su-ischool.png
        title: Faculty Assistant
        location: Syracuse University
        duration: Jan - May 2021
        text: >+ 

      - image: assets/img/logos/imec.png
        title: Internship / CO-OP
        location: Imec USA
        duration: July - Nov 2020
        text: >+
          
      - image: assets/img/logos/su-eecs.jpg
        title: Graduate Student Assistant
        location: Syracuse University Engineering Dean’s Office
        duration: Sept 2019 - June 2020
        text: >+

      - image: assets/img/logos/rolls-royce.jpeg
        title: Data Scientist
        location: Rolls Royce
        duration: Nov 2017 - July 2019
        text: >+

      - image: assets/img/logos/dpa.png
        title: Machine Learning Developer
        location: Decimal Point Analytics
        duration: Sept 2015 - Oct 2017
        text: >+  

    actions:
      - title: Education
        url: '#education'

  - type: education.html
    section_id: education
    title: Education
    background_style: bg-primary mp-0
    # background_style: bg-info text-white
    members:
      - title: Master of Science<br>Computer Science
        location: Syracuse<br>University
        duration: 2019-21
        courses: 
          - Analytical Data Mining
          - Artificial Neural Networks
          - Machine Intelligence with Deep Learning
          - Evolutionary Machine Learning
          - Reinforcement Learning
        image: assets/img/logos/syracuse-logo.png
        url: '#'
      - title:  Bachelor of Technology<br>Computer Science
        location: Symbiosis International University
        duration: 2011-15
        courses: 
          - Data Structures
          - Data Warehousing and Mining
          - Artificial Intelligence
          - Object Oriented Analysis and Design
          - Distributed Systems
        image: assets/img/logos/symbiosis-logo.jpg
        url: '#'
      - title:  Diploma in Business Management (DBM)
        location: Symbiosis Institute of Business Management
        duration: 2012-15
        courses: 
          - Entrepreneurship
          - Business Accounting and Costing
          - Financial Management
          - Economics
          - Operations Management
        image: assets/img/logos/sibm-logo.jpg
        url: '#'

    actions:
    - title: Projects
      url: '#projects'
      class: btn-dark
     
  - type: projects.html
    # background_style: bg-light
    section_id: projects
    title: Projects
    projects:
      - title: Representation Learning on Wikipedia Categories
        text: Project is aimed to understand how Representation Learning works and how it can be applied successfully to networks with an objective to obtain a low dimensional representation of a network while maintaining it's structure
        image: 'assets/img/projects/rep-learn-wiki.png'
        url: 'https://github.com/muditdham/node2vec-wiki-categories'
      - title: Time Series Anomaly Detection using Auto Encoders
        text: Leveraging the concept of Auto Encoders, this project addresses the question of how Anomaly Detection can be performed on data which is temportal in nature (time series)
        image: 'assets/img/projects/time-series-ae.png'
        url: 'https://github.com/muditdham/time-series-auto-encoder'
      - title: Solving Travelling Salesman Problem using Ant Colony Optimization
        text: The objective of this project is to explore nature inspired Ant Colony Optimization algorithm and apply it to solve the classic Travelling Salesman Problem
        image: 'assets/img/projects/aco-tsp.png'
        url: 'https://github.com/muditdham/aco-tsp'
      - title: Auto Floorplan Design for Photonic Chips and Circuits
        text: Implmentation of a packing algorithm which is space efficient while placing various circuit components together inaccordance to certain user defined constraints. 
        image: 'assets/img/projects/autofloorplan.png'
        url: 'https://github.com/muditdham/autofloorplan'
      - title: Comparitive Analysis of Community Detection Algorithms
        text: Analysis uses structural metrics such as conductance and modularity along with ground truth to analyze the quality of the communities discovered by various community detection algorithms
        image: 'assets/img/projects/comm-detection.png'
        url: 'https://github.com/muditdham/twitter-community-analysis'
      - title: 'Coming Soon'
        text: 'Currently working on it'
        image: 'assets/img/projects/coming-soon.png'
        url: '#'
    actions:
    - title: Connect
      url: '#connect'
      class: btn-dark
      
      
  # - type: aside.html
  #   section_id: aside
  #   title: Free Download at Start Bootstrap!
  #   actions:
  #     - title: Download Now!
  #       url: https://startbootstrap.com/themes/creative/
  #       class: btn-light

  # - type: members.html
  #   section_id: members
  #   title: Our Crew!
  #   background_style: bg-info text-white
  #   members:
  #     - title: Christina M. Aponte
  #       text: Singer and Songwriter
  #       image: assets/img/members/person1.jpg
  #       url: '#'
  #     - title: Gary D. Stevens
  #       text: Bass guitar.
  #       image: assets/img/members/person2.jpg
  #       url: '#'
  #     - title: Devon J. Fletcher
  #       text: Lead guitar.
  #       image: assets/img/members/person3.jpg
  #       url: '#'
  #     - title: Todd E. Anderson
  #       text: Drums, percussion.
  #       image: assets/img/members/person5.jpg
  #       url: '#'
  #     - title: Daniel T. Riley
  #       text: Musician, songwriter, producer.
  #       image: assets/img/members/person6.jpg
  #       url: '#'
  #     - title: Ella P. Walter
  #       text: PR.
  #       image: assets/img/members/person7.jpg
  #       url: '#'

  # - type: contact.html
  - type: connect.html
    section_id: connect
    title: Let's Get in Touch!
    texts:
      - Would like to connect? 
      - Follow me on LinkedIn. 
      - Send me an email and I will get back to you as soon as possible!
    actions:
    - title: Github
      icon: fa-github-square
      icon_type: fab
      url: 'https://github.com/muditdham'
    - title: LinkedIn
      icon: fa-linkedin
      icon_type: fab
      url: 'https://www.linkedin.com/in/muditdham/'
    - title: E-Mail
      icon: fab fa-envelope
      url: mailto:muditdham24@gmail.com
    - title: Twitter
      icon: fa-twitter-square
      icon_type: fab
      url: 'https://twitter.com/muditdham'
---
