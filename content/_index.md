---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: custom-biography-1
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_Sahib_Julka.pdf
    design:
      css_class: light
      background:
        color: white
        image:
          # Add your ima192.168.178.21ge background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 3.0 

          size: 30% #contain, cover or actual
          position: left
          parallax: true
  
  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |-
        - **09/2024:** Attending [ECML PKDD 2024](https://ecmlpkdd.org/2024/) in Vilnius, Lithuania, and LOD 2024 in Tuscany, Italy, to present accepted work at the respective conferences.
        - **09/2023:** Gave two talks at [LOD 2023](https://lod2023.icas.cc/wp-content/uploads/sites/23/2023/09/LOD-ACAIN-2023-Program-06.pdf) in Lake District, UK.
        - **04/2023:** Delivered two virtual presentations at [ERIM 2023](https://www.youtube.com/watch?v=-wV6LX3Zpho&t=7219s) related to the Europlanet 2024 project.
        - **09/2022:** Conducted a workshop on "Image Segmentation in planetary applications" at [EPSC 2022](https://meetingorganizer.copernicus.org/EPSC2022/session/44849) in Granada, Spain and co-convened a session on "Machine Learning in Planetary Sciences." [Session link](https://meetingorganizer.copernicus.org/EPSC2022/session/44609)
        - **09/2022:** Presented work on Deep Active Learning for the detection of Mercury's Magnetopause and Bow Shock Crossings at [ECML PKDD 2022](https://ecmlpkdd.org/2022/) in Grenoble, France.
        - **04/2022:** Co-convened a session on "Machine Learning in Planetary Science" at [EGU 2022](https://meetingorganizer.copernicus.org/EGU22/session/43559).
        - **03/2022:** Presented work from the Europlanet Project at the [AGU session on Machine Learning in Heliophysics](https://ml-helio.github.io/#Program) in Boulder, Colorado, USA.
        - **09/2021:** Gave two talks at [EPSC 2021](https://meetingorganizer.copernicus.org/EPSC2021/session/41613) and co-convened a session on "Machine Learning in Planetary Sciences."
        - **09/2021:** Presented work on Conditional GANs at [LOD 2021](https://lod2021.icas.cc/program/) in Lake District, UK.
        - **04/2021:** Gave two talks at [EGU 2021](https://meetingorganizer.copernicus.org/EGU21/sessionprogramme/ST?cosession=6095abd82abfd2-93612894-m) and co-convened a session on "Machine Learning in Planetary Science and Heliophysics."
        - **02/2020:** Attended the [Europlanet kickoff](https://www.europlanet-society.org/presentations-from-europlanet-2024-ri-kick-off-meeting/) in Windsor, UK.
        - **09/2019:** Presented top-5 winning entry at the Ariel Challenge on the estimation of dips in light curve from exoplanets at the [Data Science Challenge](https://ecmlpkdd2019.org/programme/discovery/) conducted at [ECML PKDD 2019](https://ecmlpkdd2019.org/programme/discovery/) in Würzburg, Germany.

    design:
      columns: '1'
      
   

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
      columns: 1
  
#      
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: 'test'
      text: |-
        - **Summer 2019, Winter 2020 - 2024**: [5943UE Data Science Lab](https://www.fim.uni-passau.de/data-science/lehre-und-studium/lehrveranstaltungen/personendetails?config_id=232ee5ad516ac92bf590f99ac8c2baa8&module=TemplateLecturedetails&range_id=fe6270326db54a4fa75c5fe1a5eaea48&seminar_id=c3a46e613d4eb023c9743bd8265cf3d7&cHash=7b5f01d2a9329f64fc43327adcbc4b27)
        - **Summer 2021 - 2024**: [5944UE Machine Learning Lab](https://www.fim.uni-passau.de/data-science/lehre-und-studium/lehrveranstaltungen/veranstaltungsdetails?config_id=232ee5ad516ac92bf590f99ac8c2baa8&module=TemplateLecturedetails&range_id=fe6270326db54a4fa75c5fe1a5eaea48&seminar_id=d8cef59f8abb7dc43e34560c54f884bd&target=)
       
         ** Supervised Master's and Bachelor's Theses (TODO)**
#        - Ayoub Ben Aissa, "GAN tool: Building a GAN simulator"
##             - Nikolas Kirschstein "Detection of bow shock and magnetopause crossings from MESSENGER data"
##              - Salim Fares "Exploiting SAM as an annotator for Image Segmentation"
##              - Venugopal Aswathy "Covid something something"
##              - Veena Nandimandala "Random Title"
##              - Nasrin Sayed "Random Title"
##              - Zubair Ahmad "Random Title"
##              - Aymen Chaabani "Random Title"
##              - Mehmet Can "Random Title"
##              - Hamrouni Soufien "Random Title"
##              - Yashu Wang "Random Title"
##              - Vishal Sowrirajan "Random Title"
##              - Rajat Sharma "Random Title"
##              - Rodion Ishmukhametov "Random Title"    
##            
#    design:
#      columns: '1'

#  - block: collection
#    content:
#      title: Recent Publications
#      text: ""
#      filters:
#        folders:
#          - publication
#        exclude_featured: false
#    design:
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1
#      
#  - block: collection
#    id: news
#    content:
#      title: News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 0
#      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
#        
#
#  - block: cta-card
#    demo: false # Only display this section in the Hugo Blox Builder demo site
#    content:
#      title: 👉 Build your own academic website like this
#      text: |-
#        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.
#
#        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>
#
#        Easily build anything with blocks - no-code required!
#        
#        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#      button:
#        text: Get Started
#        url: https://hugoblox.com/templates/
#    design:
#      card:
#        # Card background color (CSS class)
#        css_class: "bg-primary-700"
#        css_style: ""
---
