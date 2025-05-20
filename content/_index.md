---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: markdown
    id: home
    content:   
      title: <h4><span style="font-size:3.0rem; text-left; font-weight:600;">COLM 2025 Workshop</span><div style="height:4.0rem"></h4><h2 class="tracking-tight text-left" style="font-size:4.0rem; color:white; line-height:125%; ">Pragmatic Reasoning <br/>in Language Models<div style="height:4rem"></div></h2><h3><span style="font-size:2.1rem; text-left; font-weight:400; font-style:italic">Language Models as Language Users</span><div style="height:8.0rem"></h3><h2 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; "><span style="font-size:2.5rem; text-align:left; display:block; border-left:10px solid white; padding-left:1rem; font-weight:500; line-height:150%;">October 10, 2025 <br/>Montreal, Canada </span></h2>
      # text: 
    design:
    
      spacing:
        padding: ["5rem", 0, 0, 0]
      columns: 1
      css_class: "dark"
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

  - block: cta-card
    content:
      title: <h2 class="tracking-tight text-left" style="font-size:2.0rem; color:white; line-height:125%; "> Register and Join Us!</h2>
      text: 
      button:
        text: Main Conference
        url: https://colmweb.org
    design:
      card:
        css_class: "bg-transparent"
      spacing:
        padding: [0,0,"5rem",0]
      columns: 1
      css_class: "dark"
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
          <span style="font-size:1.6rem; text-left; font-weight:600;"> 
          Humans are pragmatic language users</span><br/>
          We produce language based on our understanding of how context contributes to meaning and deliberate on the choice of utterances and interpretations that helps us collaborate and engage in social interactions. 
          While recent large language models (LLMs) have shown impressive performance on a variety of language-related tasks, could these models be considered as true pragmatic language users?
          <br/>
          <br/>

          <h4 style="font-size:1.2rem; text-left; font-weight:400;">
          <span style="font-size:1.6rem; text-left; font-weight:600;"> 
          Towards Language Models as Language Users</span><br/>
          <span style="text-left;font-family: 'Source Serif 4', serif; font-weight:700; letter-spacing: 0em;"> The 1st Workshop on Pragmatic Reasoning in Language Models (PragLM)</span> 
          aims to stimulate research on LLMs as pragmatically competent language users.
          We invite contributions that will forward the discussion of understanding and improvent of LLMs' capability to generate natural language flexibly and efficiently across contexts, with relations to research on the cognitive and linguistic processes supporting effective, context-sensitive communication. Our interdisciplinary theme brings together researchers in NLP, comptuational pragmatics, cognitive science, and other fields: <br/>join us at COLM 2025!
          </h4>
        </div>
    design:
      spacing:
        padding: ["5rem", 0, "5rem", 0]
      columns: 1
      css_class: "dark"
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
            We invite researchers to present their published and ongoing works on the topics of, but not limited to:
          </h4>

          <div>
            <h4 style="font-size:1.2rem; text-center; font-weight:400; margin-bottom:2rem;">
              <ul style="list-style-type:disc; padding-left:1.5rem; margin-top:1rem;">
              <details style="color:white; margin-bottom:1rem;">
                  <summary style="color:#C3EEFA; cursor:pointer; font-size:1.2rem; margin-top:0rem;margin-bottom:1rem;">Improving Pragmatic, Contextual Language Use in LLMs</summary>
                    How can LLMs' pragmatic abilities be improved and made more human-like, and how should human-likeness in pragmatic competence be assessed?
                </details>
               <details style="color:white; margin-bottom:1rem;">
                  <summary style="color:#C3EEFA; cursor:pointer; font-size:1.2rem; margin-top:0rem;margin-bottom:1rem;">Evaluating  Pragmatic Competence of Language Models</summary>
                    How well can LLMs comprehend and/or generate pragmatic language, across task formats and prompting strategies? 
                    <br/> What are key considerations for designing benchmarks and evaluation frameworks?
                </details>
                <details style="color:white; margin-bottom:1rem;">
                  <summary style="color:#C3EEFA; cursor:pointer; font-size:1.2rem; margin-top:0rem;margin-bottom:0.5rem;">Theory-of-Mind (ToM) and Pragmatics</summary>
                    Is there a correlation between LLM capabilities for Theory-of-Mind reasoning and contextual language generation? If so, what are the mechanisms behind these capabilities?
                </details>
                <details style="color:white; margin-bottom:1rem;">
                  <summary style="color:#C3EEFA; cursor:pointer; font-size:1.2rem; margin-top:0rem;margin-bottom:0.5rem;">Pragmatics across Cultures and Languages</summary>
                    Are LLM abilities in functional language use similar across cultural contexts and languages?
                </details>
                <details style="color:white; margin-bottom:1rem;">
                  <summary style="color:#C3EEFA; cursor:pointer; font-size:1.2rem; margin-top:0rem;margin-bottom:0.5rem;">
                    Application of LLMs for Understanding <br/>Human Pragmatic Language Use</summary>
                    How can LLMs be leveraged for better theoretical, experimental and computational understanding of human pragmatic language use?
                </details>
                <details style="color:white; margin-bottom:1rem;">
                  <summary style="color:#C3EEFA; cursor:pointer; font-size:1.2rem; margin-top:0rem;margin-bottom:0.5rem;">Interpretability of LLMs' Pragmatic Competence </summary>
                    What are the mechanisms supporting LLMs' pragmatic competence, e.g. through the lens of mechanistic or representational interpretability?
                </details>
              </ul>
          </div>

          <br/>

          <h2 style="font-size:1.5rem; margin-bottom:1rem;">Submission Format</h2>
          <div>
            <h4 style="font-size:1.1rem; text-left; font-weight:400; margin-bottom:2rem;">
            We seek <strong>both 4-page extended abstracts and 8-page full papers</strong> excluding references and appendices. All workshops papers are <strong> non-archival </strong>, and we welcome <strong> position</strong>  papers on topics of interest to the workshop. 
            <br/><br/>
            All submissions will be in the <a href="https://github.com/COLM-org/Template/archive/refs/tags/2025.zip" style="color:#C3EEFA;">COLM 2025 latex format</a> and submitted via the OpenReview portal. Accepted papers will be invited for poster/oral presentations and will be publicly available on the workshop website.
            </h4>
          </div>
        </div>

    design:
      spacing:
        padding: ["5rem", 0, 0, 0 ]
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
  - block: cta-card
    content:
      title: 
      text: 
      button:
        text: Submit now!
        url: https://openreview.net/group?id=colmweb.org/COLM/2025/Workshop/PragLM
    design:
      card:
        css_class: "bg-transparent"
      spacing:
        padding: [0,0,"5rem",0]
      columns: 1
      css_class: "dark"
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
        padding: ["5rem", 0, "10rem", 0]
      columns: 1
      css_class: "dark"
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

  # - block: cta-card
  #   content:
  #     title: 
  #     text: 
  #     button:
  #       text: OpenReview Submission
  #       url: TBD
  #   design:
  #     card:
  #       css_class: "bg-transparent"
  #     spacing:
  #       padding: [0,0,"5rem",0]
  #     columns: 1
  #     css_class: "dark"
  #     background:
  #       color: "#111111"
  #       image:
  #         filename: 1.png
  #         size: contain
  #         position: center
  #         # Use a fun parallax-like fixed background effect on desktop? true/false
  #         parallax: true
  #         # Text color (true=light, false=dark, or remove for the dynamic theme color).
  #         text_color_light: true

  - block: markdown
    id: speakers
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Invited Speakers<hr/></h1>
      #<img src="speakers/bg-triangles.svg" width="250" height="250" alt="Jane Doe">
      text: |
        <div style="width: 100%; margin: 0 auto; display: grid; grid-template-columns: repeat(4, auto); gap: 2rem; justify-content: center; text-align: center;">
          
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

          <div>
            <h3 style="font-size: 1.5rem; margin: 0.5rem 0;"><strong>Michael Franke</strong></h3>
           <p style="font-size: 1rem;">
            University of Tübingen</p>
          </div>
    design:
      spacing:
        padding: ["5rem", 0 , 0, 0]
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


  - block: markdown
    id: schedule
    content:
      title: <h1 class="tracking-tight text-left" style="font-size:3rem; color:white; line-height:125%; ">Tentative Schedule<hr/></h1>
      text: |
        <div style="font-size:1.3rem; text-left; font-weight:400; max-width:1200px; margin:0 auto; color:white">
          <table style="width:100%; border-collapse: collapse; table-layout:fixed;">
            <tr>
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">9:00 - 9:15</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Opening Remarks</td>
            </tr>
            <tr>
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">9:15 - 10:00</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Keynote: TBD</td>
            </tr>
            <tr>
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">10:00 - 10:45</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Keynote: TBD</td>
            </tr>
            <tr style="background-color:rgba(225, 179, 29, 0.16);">
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">10:45 - 11:00</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Coffee Break ☕</td>
            </tr>
            <tr>
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">11:00 - 12:00</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Contributed Talks Session (Oral)</td>
            </tr>
            <tr>
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">1:00 - 1:45</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Keynote: TBD</td>
            </tr>
            <tr style="background-color:rgba(225, 179, 29, 0.16);">
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">1:45 - 3:00</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Coffee Break ☕ and Poster Session</td>
            </tr>
            <tr>
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">3:00 - 3:45</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Keynote: TBD</td>
            </tr>
            <tr">
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">3:45 - 4:30</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Panel Discussion</td>
            </tr>
            <tr>
              <td style="width:30%; padding:1rem; border-bottom:1px solid #e5e5e5;">4:30 - 4:50</td>
              <td style="width:70%; padding:1rem; border-bottom:1px solid #e5e5e5;">Best Paper Awards; Closing Remarks</td>
            </tr>
          </table>
        </div>
    design:
      spacing:
        padding: ["5rem", 0, "5rem", 0]
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
        padding: ["10rem", 0, 0, 0]
      columns: 1
      css_class: "dark min-h-screen"
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
        padding: ["10rem", 0, "5rem", 0]
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
