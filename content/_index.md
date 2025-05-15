---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: markdown
    id: intro
    content:   
      title: <h4><span style="font-size:3.0rem; text-left; font-weight:600;">COLM 2025 Workshop</span><div style="height:4.0rem"></h4><h2 class="tracking-tight text-left" style="font-size:4.0rem; color:white; line-height:125%; ">Pragmatic Reasoning <br/>in Language Models<div style="height:4rem"></div></h2><h3><span style="font-size:2.1rem; text-left; font-weight:400; font-style:italic">Language Models as Language Users</span><div style="height:8.0rem"></h3><h2 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; "><span style="font-size:2.5rem; text-align:left; display:block; border-left:10px solid white; padding-left:1rem; font-weight:500; line-height:150%;">October 10, 2025 <br/>Montreal, Canada </span></h2>
      # text: 
    design:
    
      spacing:
        padding: ["10rem", "10rem", 0 , 0]
      columns: 1
      css_class: "dark min-h-screen"
      background:
        color: "#111111"
        image:
          filename: 1.png
          size: contain
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  - block: markdown
    id: overview
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Overview<hr/></h1>
      text: |
        <div> 
          <h4 style="font-size:1.2rem; text-left; font-weight:400;">
            Our workshop at COLM 2025 aims to invite research to uncover how modern LLMs may or may not already be, or could be trained or enhanced as, pragmatically competent pragmatic language users. We invite contributions that will help to forward the discussion of understanding LLMs, beyond the formal capabilities to functional linguistic capabilities that would allow models to use natural language flexibly and efficiently across contexts. Our workshop serves as an opportunity for researchers in NLP, (computational) pragmatics, cognitive science, and related interdisciplinary fields to come together in investigating this timely research direction.
          </h4>
        </div>
    design:
      spacing:
        padding: ["5rem", "10rem", 0, 0]
      columns: 1
      css_class: "dark "
      background:
        color: "#111111"
        image:
          filename: 1.png
          size: contain
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
  

  - block: markdown
    id: cfp
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Call for Contributions<hr/></h1>
      text: |
        <div> 
          <h4 style="font-size:1.2rem; text-left; font-weight:400; margin-bottom:2rem;">
            We invite papers conforming to the COLM main track guidelines on research questions including, but not limited to:
          </h4>

          <div>
            <h4 style="font-size:1.1rem; text-left; font-weight:400; margin-left:2rem; margin-bottom:3rem;">
            <ul style="list-style-type:disc;">
              <li style="margin-bottom:1rem;">How well can LLMs comprehend and/or generate pragmatic language, across task formats and prompting strategies?</li>
              <li style="margin-bottom:1rem;">How can LLMs' pragmatic abilities be improved and made more human-like, and how should human-likeness in pragmatic competence be assessed?</li>
              <li style="margin-bottom:1rem;">s there a correlation between LLM capabilities for Theory-of-Mind reasoning and contextual language generation; if so, how?</li>
              <li style="margin-bottom:1rem;">Are LLM abilities in functional language use similar across cultures and languages?</li>
              <li style="margin-bottom:1rem;">How can LLMs' pragmatic abilities be improved and made more human-like, and how should human-likeness in pragmatic competence be assessed?</li>
              <li style="margin-bottom:1rem;">How can LLMs be leveraged for better theoretical, experimental and computational understanding of human pragmatic language use?</li>
              <li style="margin-bottom:1rem;">What are the mechanisms supporting LLMs' pragmatic competence, e.g. through the lens of mechanistic or representational interpretability?</li>
            </ul>
          </div>

          <h2 style="font-size:1.5rem; margin-bottom:1rem;">Submission Format</h2>
          <div>
            <h4 style="font-size:1.1rem; text-left; font-weight:400; margin-bottom:2rem;">
            We seek <strong>both short and long papers</strong> (up to 4 and 8 pages, respectively) excluding references and appendices. All submissions will be in PDF format and submitted via the OpenReview portal. Reviews will be double-blind. All accepted papers are non-archival.
            </h4>
          </div>
        </div>
    design:
      spacing:
        padding: ["10rem", "12rem", "10rem", 0 ]
      columns: 1
      css_class: "dark min-h-screen"
      background:
        color: "#111111"
        image:
          filename: 1.png
          size: contain
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  - block: markdown
    id: dates
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Important Dates<hr/></h1>
      text: |
        <div>
            <h4 style="font-size:1.3rem; text-left; font-weight:400;">
            <ul style="list-style-type:none;">
              <li style="margin-bottom:0.5rem;">📅 <strong>Submission open:</strong> TBD</li>
              <li style="margin-bottom:0.5rem;">📅 <strong>Submission deadline:</strong> June 23rd AoE</li>
              <li style="margin-bottom:0.5rem;">📅 <strong>Notification of acceptance:</strong> July 24th</li>
              <li style="margin-bottom:0.5rem;">📅 <strong>Camera-ready due:</strong> TBD</li>
              <li style="margin-bottom:0.5rem;">📅 <strong>Workshop date:</strong> October 10th</li>
            </ul>
            </h4>
        </div>
    design:
      spacing:
        padding: ["10rem", 0, 0, "10rem"]
      columns: 1
      css_class: "dark"
      background:
        color: "#111111"
        image:
          filename: 2.png
          size: contain
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  - block: markdown
    id: speakers
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Invited Speakers<hr/></h1>
      #<img src="speakers/bg-triangles.svg" width="250" height="250" alt="Jane Doe">
      text: |
        <div style="width: 100%; margin: 0 auto; display: grid; grid-template-columns: repeat(3, 0fr); gap: 2rem; text-align: center;">
          
          <div>
            <h3 style="font-size: 1.5rem; margin: 0.5rem 0;"><strong>Daniel Fried</strong></h3>
            <p style="font-size: 1rem;">
            CMU </p>
          </div>

          <div>
            <h3 style="font-size: 1.5rem; margin: 0.5rem 0;"><strong>Jennifer Hu</strong></h3>
            <p style="font-size: 1rem;">
            Harvard/JHU </p>
          </div>

          <div>
            <h3 style="font-size: 1.5rem; margin: 0.5rem 0;"><strong>Vera Demberg</strong></h3>
           <p style="font-size: 1rem;">
            Saarland University</p>
          </div>
    design:
      spacing:
        padding: ["10rem", 0 , 0, "10rem"]
      columns: 1
      css_class: "dark min-h-screen"
      background:
        color: "#111111"
        image:
          filename: 2.png
          size: contain
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  # - block: cta-card
  #   content:
  #     title: Register Today!
  #     text: Main Conference Registration
  #     button:
  #       text: Register
  #       url: https://colmweb.org
  #   # design:
  #   #   card:
  #   #     # Card background color (CSS class)
  #   #     css_class: "bg-primary-700"
  #   #     css_style: ""
  #   design:
  #     card:
  #       css_class: 
  #       css_style: "dark min-h-screen"
  #     spacing:
  #       padding: [0, 0, "10rem", 0]
  #     columns: 1
  #     css_class: "dark "
  #     background:
  #       color: "#111111"
  #       image:
  #         filename: 3.png
  #         size: contain
  #         position: center
  #         # Use a fun parallax-like fixed background effect on desktop? true/false
  #         parallax: true
  #         # Text color (true=light, false=dark, or remove for the dynamic theme color).
  #         text_color_light: true

  - block: markdown
    id: schedule
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Schedule<hr/></h1>
      text: TBD
        # |
        # <div style="font-size:1.2rem; text-left; font-weight:400;">
        #   <table style="width:100%; border-collapse: collapse;">
        #     <tr>
        #       <th style="width:50%; padding:1rem; border-bottom:1px solid #444444; color:white; font-size:1.4rem;">Morning</th>
        #       <th style="width:50%; padding:1rem; border-bottom:1px solid #444444; color:white; font-size:1.4rem;">Afternoon</th>
        #     </tr>
        #     <tr>
        #       <td style="padding:1rem; vertical-align:top;">
        #         <h4 style="font-size:1.2rem; font-weight:400;">
        #           <strong>9:00 - 9:15</strong><br/>
        #           <span style="color:#888888">Opening Remarks</span>
        #           <br/><br/>
        #           <strong>9:15 - 10:00</strong><br/>
        #           <span style="color:#888888">Keynote: Daniel Fried</span>
        #           <br/><br/>
        #           <strong>10:00 - 10:45</strong><br/>
        #           <span style="color:#888888">Keynote: Jennifer Hu</span>
        #           <br/><br/>
        #           <strong>10:45 - 11:00</strong><br/>
        #           <span style="color:#888888">Coffee Break</span>
        #           <br/><br/>
        #           <strong>11:00 - 12:30</strong><br/>
        #           <span style="color:#888888">Contributed Talks Session 1</span>
        #         </h4>
        #       </td>
        #       <td style="padding:1rem; vertical-align:top;">
        #         <h4 style="font-size:1.2rem; font-weight:400;">
        #           <strong>2:00 - 2:45</strong><br/>
        #           <span style="color:#888888">Keynote: Vera Demberg</span>
        #           <br/><br/>
        #           <strong>2:45 - 3:30</strong><br/>
        #           <span style="color:#888888">Keynote: Michael Franke</span>
        #           <br/><br/>
        #           <strong>3:30 - 3:45</strong><br/>
        #           <span style="color:#888888">Coffee Break</span>
        #           <br/><br/>
        #           <strong>3:45 - 5:15</strong><br/>
        #           <span style="color:#888888">Contributed Talks Session 2</span>
        #           <br/><br/>
        #           <strong>5:15 - 5:30</strong><br/>
        #           <span style="color:#888888">Closing Remarks</span>
        #         </h4>
        #       </td>
        #     </tr>
        #   </table>
        # </div>
    design:
      spacing:
        padding: ["10rem", 0, "20rem", "10rem"]
      columns: 1
      css_class: "dark"
      background:
        color: "#111111"
        image:
          filename: 2.png
          size: contain
          position: center
          parallax: true
          text_color_light: true


  - block: markdown
    id: organizers
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Organizers<hr/></h1>
      text: |
        <div style="font-size:1.2rem; text-left; font-weight:400;">
          <ul style="list-style-type:none;">
            <h4 style="font-size:1.2rem; text-left; font-weight:400;">
              <li style="margin-bottom:0.3rem;">• Alane Suhr <span style="color:#BBBBBB">, University of California at Berkeley</span></li>
              <li style="margin-bottom:0.3rem;">• Anya Ji <span style="color:#BBBBBB">, University of California at Berkeley</span></li>
              <li style="margin-bottom:0.3rem;">• Kayo Yin <span style="color:#BBBBBB">, University of California at Berkeley</span></li>
              <li style="margin-bottom:0.3rem;">• Minwoo Kang <span style="color:#BBBBBB">, University of California at Berkeley</span></li>
              <li style="margin-bottom:0.3rem;">• Nicholas Tomlin <span style="color:#BBBBBB">, University of California at Berkeley</span></li>
              <li style="margin-bottom:0.3rem;">• Polina Tsvilodub <span style="color:#BBBBBB">, University of Tübingen</span></li>
              <li style="margin-bottom:0.3rem;">• Robert Hawkins <span style="color:#BBBBBB">, Stanford University</span></li>
              <li style="margin-bottom:0.3rem;">• Seun Eisape <span style="color:#BBBBBB">, University of California at Berkeley</span></li>
              <li style="margin-bottom:0.3rem;">• Téa Wright <span style="color:#BBBBBB">, University of California at Berkeley</span></li>
            </h4>
          </ul>
        </div>
    design:
      spacing:
        padding: ["10rem", "10rem", 0, 0]
      columns: 1
      css_class: "dark"
      background:
        color: "#111111"
        image:
          filename: 3.png
          size: contain
          position: center
          parallax: true
          text_color_light: true


  - block: markdown
    id: contact
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Contact<hr/></h1>
      text: |
        <div style="font-size:1.2rem; text-left; font-weight:400;">
          <h4 style="font-size:1.2rem; text-left; font-weight:400;">
            <p>&#9993; <a href="mailto:workshop.pragmatics.llms@gmail.com" style="color:#888888;">workshop.pragmatics.llms@gmail.com</a></p>
          </h4>
        </div>
    design:
      spacing:
        padding: ["10rem", "10rem", "5rem", 0]
      columns: 1
      css_class: "dark"
      background:
        color: "#111111"
        image:
          filename: 3.png
          size: contain
          position: center
          parallax: true
          text_color_light: true
---
