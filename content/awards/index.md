---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-12-27
type: landing

sections:
  - block: collection
    content:
      title: Awards
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: MS in Bioinformatics Scholarship ($10K)
          company: Boston University 
          company_url: ''
          company_logo: bu
          location: Boston, USA
          date_start: '2017-09-01'
          date_end: '2018-05-30'
          description: |2-
              * Incoming MS student scholarship for merit-based students.
        - title: Scientific Programmer @<u><a href = https://www.bu.edu/hic/profile/evan-johnson/>Johnson Lab </a></u>
          company: Boston University Chobanian & Avedisian School of Medicine
          company_url: ''
          company_logo: bu
          location: Boston, USA
          date_start: '2018-06-01'
          date_end: '2019-06-30'
          description: |2-
              * Co-developed <i> sctk </i>: a single-cell analysis toolkit with a user interface to ease downstream analyses.
              * Experienced in code release management and maintenance specifically for Bioconductor R packages
        - title: Software Analyst
          company: Accenture Services Pvt Ltd.
          company_url: ''
          company_logo: accenture_logo
          location: Bangalore, India
          date_start: '2014-11-01'
          date_end: '2019-07-31'
          description: |2-
              * Developed Selenium and Jenkins automated testing suite for code sanity checks in remote environments, increased performance by 33%,
                and halved FTE using Agile/SCRUM methodology
    design:
      columns: '2'
---

