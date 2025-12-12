---
title: 'Home'
date: 2025-11-10 # Current date
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # === 1. HERO BLOCK: Title, Dates, Host ===
  - block: hero
    content:
      title: '<span class="gradient-animate">ACM India Winter School on Edge AI</span>'
      text: |
        <br><br>
        **28 December 2025 to 4 January 2026**<br><br>
        **Venue:** CDS building, Indian Institute of Science (IISc), Bengaluru<br><br>
        <div style="margin-top: 10px; text-align: center;">
          <img src="iisc-logo-black.png"
               alt="IISc Logo"
               style="max-height: 250px; max-width: 120%; display: inline-block;">
        </div>
        <br>   
    design:
      min_height: "100vh"   # 90% of screen height (increase if needed)    
      spacing:
        padding: ["40px", "0", "40px", "120px"]
        margin: ["0", "0", "0", "0"]      
      css_class: "hero-block light"
      background:
        color: "white"
        image:
          filename: bg-iisc4-min.png
          filters:
            brightness: 0.2
          size: cover
          position: top
          parallax: true

    
  # === 2. ABOUT BLOCK: Description, Background, Software (WIDER & JUSTIFIED VIA CUSTOM CSS) ===
  - block: markdown
    id: about
    content:
      title: About the School
      text: |
        <p style="text-align: justify;">
        
        The **<a href="https://india.acm.org/education/acm-india-winter-schools-2025/">ACM India Winter School on Edge AI</a>** will provide an in-depth overview of software platforms, hardware systems, and AI models and algorithms for efficient deployment on accelerated and classic edge devices. The program will cover topics suchs as edge computing architectures and accelerators, co-optimization techniques of edge systems and ML models for performance, power and accuracy, federated learning frameworks, and the deployment of AI, generative AI/LLM models and AI agents at the edge for practical and IoT applications suchs as smart mobility and smart agriculture. Through lectures, hands-on sessions, and expert talks, participants will gain practical skills to design, implement, and optimize intelligent edge systems for diverse real-world applications.
        </p>
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      columns: 1
      spacing:
        padding: ["6rem","0","6rem","0"]

# === 3. TOPICS BLOCK (FINAL FIX: Emojis Embedded in Name Field) ===
  - block: features
    id: topics
    content:
      title: Key Topics
      text: |
        The winter school covers foundational and advanced aspects of Edge AI.
      items:
        - name: "<span style=\"font-size: 2.5rem;\">🏡</span> <br><br>Foundations of IoT, Accelerated Edge Computing and Edge AI"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">💾</span> <br><br>Tiny and Embedded Machine Learning"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🚀</span> <br><br>Model Optimization and Acceleration for Edge AI"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">⚙️</span> <br><br>Edge AI Platforms, Frameworks, and Deployment Pipelines"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🌐</span> <br><br>Federated Learning and Distributed Training for Edge Devices"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🧠</span> <br><br>Neuromorphic Computing and Brain-Inspired Architectures"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">✨</span> <br><br>Generative AI and LLM at the Edge"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🤖</span> <br><br>Agentic AI on the Edge"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🛡️</span> <br><br>Security, Privacy, and Responsible AI in Edge Systems"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">📊</span> <br><br>Benchmarking, Profiling, and Performance Evaluation of Edge AI Systems"
          icon: ""
        - name: "<span style=\"font-size: 2.5rem;\">🛰️</span> <br><br>Edge AI for Drones/UAVs, IoT, Smart Cities, and Industrial Applications"
          icon: ""
    design:
      css_class: ""
      columns: 3

# === 4. SPEAKERS BLOCK (4-COLUMN GRID FIX) ===
  - block: features
    id: speakers
    content:
      title: 🎤 Speakers
      text: |
        <br><br>
        ### **Keynote Speakers**
        
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1200px; margin: 0 auto;">
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;"> 
          <a href="https://edge.seas.harvard.edu/people/vijay-janapa-reddi">
            <img src="speaker_vijay.jpg" alt="Photo of Vijay Janappa Reddi" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://edge.seas.harvard.edu/people/vijay-janapa-reddi"><strong>Vijay Janappa Reddi</strong></a><br/>Harvard University</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://isc.mst.edu/people/ri/sdas/">
            <img src="speaker_sajal.jpg" alt="Photo of Sajal Das" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://isc.mst.edu/people/ri/sdas/"><strong>Sajal Das</strong></a><br/>Missouri Univ. of Sci. & Tech, USA</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://ojhavk.github.io/">
            <img src="speaker_varun.jpg" alt="Photo of Varun Ojha" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://ojhavk.github.io/"><strong>Varun Ojha</strong></a><br/>New Castle University, UK</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://sites.google.com/view/archan-misra">
            <img src="speaker_archan.jpg" alt="Photo of Archan Misra" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://sites.google.com/view/archan-misra"><strong>Archan Misra</strong></a><br/>SMU</p>
        </div>
        
        </div>

        <br><br>
        ### **Technical Session Speakers**
        
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1200px; margin: 0 auto;">
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://iitbhu.ac.in/dept/cse/people/ajaycse">
            <img src="speaker_ajay.jpg" alt="Photo of Ajay Pratap" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://iitbhu.ac.in/dept/cse/people/ajaycse"><strong>Ajay Pratap</strong></a><br/>IIT Bhuvaneswar</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;"> 
          <a href="https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan">
            <img src="speaker_gayathri.jpg" alt="Photo of Gayathri Ananthanarayanan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan"><strong>Gayathri Ananthanarayanan</strong></a><br/>IIT Dharwad</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://www.bits-pilani.ac.in/hyderabad/manik-gupta">
            <img src="speaker_manik.jpg" alt="Photo of Manik Gupta" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.bits-pilani.ac.in/hyderabad/manik-gupta"><strong>Manik Gupta</strong></a><br/>BITS Pilani</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://www.samy101.com/">
            <img src="speaker_pandarasamy.jpg" alt="Photo of Pandarasamy Arjunan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.samy101.com/"><strong>Pandarasamy Arjunan</strong></a><br/>IISc</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://cds.iisc.ac.in/faculty/simmhan/">
            <img src="speaker_yogesh.jpg" alt="Photo of Yogesh Simmhan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://cds.iisc.ac.in/faculty/simmhan/"><strong>Yogesh Simmhan</strong></a><br/>IISc</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://www.punitrathore.com/home">
            <img src="speaker_punit.jpg" alt="Photo of Punit Rathore" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.punitrathore.com/home"><strong>Punit Rathore</strong></a><br/>IISc</p>
        </div> 
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://eecs.iisc.ac.in/people/chetan-singh-thakur/">
            <img src="speaker_chetan.jpg" alt="Photo of Chetan Singh Takur" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://eecs.iisc.ac.in/people/chetan-singh-thakur/"><strong>Chetan Singh Takur</strong></a><br/>IISc</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://www.csa.iisc.ac.in/~skmandal">
            <img src="speaker_sumit.jpg" alt="Photo of Sumit Kumar Mandal" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://www.csa.iisc.ac.in/~skmandal"><strong>Sumit Kumar Mandal</strong></a><br/>IISc</p>
        </div>
  
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;"> 
          <a href="https://prakadambi.github.io/">
            <img src="speaker_prashanti.jpeg" alt="Photo of Prashanti" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://prakadambi.github.io/"><strong>Prashanti</strong></a><br/>AMD</p>
        </div>
        
        <div style="width: 20%; min-width: 100px; margin: 40px 10px;">
          <a href="https://sites.google.com/site/prasantmisra/">
            <img src="speaker_prasant.jpg" alt="Photo of Prasant Misra" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #90A2AF;">
          </a>
          <p><a href="https://sites.google.com/site/prasantmisra/"><strong>Prasant Misra</strong></a><br/>TCS Research</p>
        </div>
  
        </div>
        
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      view: compact
      columns: 1 # Set to 1 because the columns are defined by inline HTML width

# === 5. PROGRAMS (NEW SECTION) ===
  - block: features
    id: program
    content:
      title: 📅 Program
      text: |
        <br><br>
        ## 🍽️ Common Meal Times
        <p style="text-align: center; font-size: 1.1em; line-height: 1.6;">
        <strong>Breakfast:</strong> 8:00 – 9:00 AM Daily<br>
        <strong>Dinner / Social:</strong> 7:00 – 8:00 PM Daily
        </p>
  
        ---
  
        ### 📚 Session Legend
        <div style="max-width: 650px; margin: 0 auto; padding: 15px 0;">
        <ul style="list-style-type: none; padding-left: 0; text-align: center;">
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#F5F7F8; padding:4px 10px; border-radius:4px; margin-right:4px;">☕ Break / Meal</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#F7E8FF; padding:4px 10px; border-radius:4px; margin-right:4px;">🎤 Keynote / Invited Talk</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#E8F1FF; padding:4px 10px; border-radius:4px; margin-right:4px;">👨‍🏫 Lecture / Technical Talk</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#FFF3E8; padding:4px 10px; border-radius:4px; margin-right:4px;">🧪 Lab / Tutorial</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#DE9F32; padding:4px 10px; border-radius:4px; margin-right:4px;">🏢 Industry Session</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#E6F5E6; padding:4px 10px; border-radius:4px; margin-right:4px;">💻 Hackathon</span></li>
          <li style="display: inline-block; margin: 5px 8px;"><span style="background-color:#CCF4B1; padding:4px 10px; border-radius:4px; margin-right:4px;">🎉 Closing Ceremony</span></li>
        </ul>
        </div>
  
        ---    
        
        <br><br>      
        <h3><strong>Day 1 – 28th Dec 2025</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Vijay Janappa Reddi (Harvard University)</td><td style="padding:8px;">Edge AI: Opportunities and Challenges</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Chetan Singh Takur (IISc)</td><td style="padding:8px;">Introduction to Edge AI hardware systems</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Chetan Singh Takur (IISc)</td><td style="padding:8px;">Introduction to Edge AI hardware systems</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML Lab</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML Lab</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 2 – 29th Dec 2025</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <!-- tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Sumit Kumar Mandal (IISc)</td><td style="padding:8px;">Technical Session</td></tr -->
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Gayathri Ananthanarayanan (IIT Dharwad)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Gayathri Ananthanarayanan (IIT Dharwad)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision Lab</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision Lab</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 3 – 30th Dec 2025</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Prashanti (AMD)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators Lab</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators Lab</td></tr>
        </tbody></table>
        <br><br>   
        <h3><strong>Day 4 – 31st Dec 2025</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">FL on Edge Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Varun Ojha (New Castle)</td><td style="padding:8px;">Invited Talk</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Varun Ojha (New Castle)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">FL on Edge Lab</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 5 – 1st Jan 2026</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Sumit Kumar Mandal (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Sumit Kumar Mandal (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Prasant Misra (IISc & TCS)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Punit Rathore (IISc)</td><td style="padding:8px;">Hands-on Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Gen AI at Edge Lab</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Gen AI at Edge Lab</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 6 – 2nd Jan 2026</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Sajal Das (Missouri)</td><td style="padding:8px;">Technical Talk</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">IoT Analytics Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#DE9F32;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">—</td><td style="padding:8px;">MATLAB Session</td></tr>
        <tr style="background-color:#DE9F32;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">—</td><td style="padding:8px;">Reserved</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 7 – 3rd Jan 2026</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Archan Misra (SMU)</td><td style="padding:8px;">Technical Talk</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Ajay Pratap (IIT Bhu)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Ajay Pratap (IIT Bhu)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#DE9F32;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">—</td><td style="padding:8px;">Arm Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">4:00 – 5:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Work Session</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">5:30 – 7:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Work Session</td></tr>
        </tbody></table>
        <br><br>      
        <h3><strong>Day 8 – 4th Jan 2026</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>  
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">9:00 – 12:45 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Work Session</td></tr>      
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>      
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">2:00 – 3:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Demo/Presentation</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">4:00 – 5:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Demo/Presentation</td></tr>
        <tr style="background-color:#CCF4B1;"><td style="padding:8px;">5:30 – 7:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Certificate Distribution and Closing</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">7:00 – 8:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Dinner / Social</td></tr>
        </tbody></table>
        <br><br>      

    design:
      columns: 1
      css_class: ""
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]

# === 6. LOGISTICS AND MAPS (NEW SECTION) ===
  - block: markdown
    id: venue
    content:
      title: 📍 Venue
      text: |
        This Program is hosted at the **CDS building, Indian Institute of Science (IISc), Bengaluru**.
        
        ### Location and Access
        * **Location:** The IISc campus is easily accessible from all parts of Bengaluru. The nearest metro station is **Yeshwanthpur**.
        * **Venue Map:** The CDS building is located near the main administrative block. <a href="https://maps.app.goo.gl/Sygki6ResDbrqMEy9">
          <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="location-dot" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" data-fa-i2svg="" style="display: inline-block; height: 1em; margin-left: 0.5em;"><path fill="currentColor" d="M168.3 499.2C116.1 435 0 279.4 0 192C0 85.96 85.96 0 192 0C298 0 384 85.96 384 192C384 279.4 267 435 215.7 499.2C203.4 514.5 180.6 514.5 168.3 499.2H168.3zM192 256C227.3 256 256 227.3 256 192C256 156.7 227.3 128 192 128C156.7 128 128 156.7 128 192C128 227.3 156.7 256 192 256z"></path></svg> Click Here
          </a>
        
    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]

# === 7. Contact Us ===
  - block: markdown
    id: contacts
    content:
      title: 📧 Contact Us
      text: |
        If you have any **logistical or academic questions** regarding the Winter School, please reach out to the program coordinators below.
  
        1. **Pandarasamy Arjunan** (IISc)
            * **Profile:** [https://www.samy101.com/](https://www.samy101.com/)
            * **Email:** [samy@iisc.ac.in](mailto:samy@iisc.ac.in)
  
        2. **Yogesh Simmhan** (IISc)
            * **Profile:** [https://cds.iisc.ac.in/faculty/simmhan/](https://cds.iisc.ac.in/faculty/simmhan/)
            * **Email:** [simmhan@iisc.ac.in](mailto:simmhan@iisc.ac.in)
  
    design:
      columns: 1
      css_class: ""
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]
      

  # === 8. SPONSORS / SUPPORTED BY (NEW SECTION WITH LOGOS) ===
  - block: markdown
    id: sponsors
    content:
      title: Sponsored By
      text: |
        <div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 30px; margin-top: 30px;">
        
          <a href="https://india.acm.org/" target="_blank">
            <img src="acm-logo.png" alt="ACM India Council" style="max-height: 100px; width: auto;">
          </a>
          
          <a href="https://www.iisc.ac.in/" target="_blank">
            <img src="iisc_logo.png" alt="IISc" style="max-height: 100px; width: auto;">
          </a>

          <a href="https://rbccps.org/" target="_blank">
            <img src="rbccps-logo.png" alt="RBCCPS" style="max-height: 100px; width: auto;">
          </a>

          <a href="https://artpark.in/" target="_blank">
            <img src="ARTPARK-logo.png" alt="ARTPARK" style="max-height: 100px; width: auto;">
          </a>
          
          <a href="https://cds.iisc.ac.in/" target="_blank">
            <img src="cds_logo.png" alt="CDS" style="max-height: 100px; width: auto;">
          </a>

        </div>
        
    design:
      columns: 1
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
        color: white
      spacing:
        padding: ["3rem","0","3rem","0"]
---
