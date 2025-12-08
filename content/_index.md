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
    id: top
    content:
      title: ""
      text: |
        <div class="hero-svg-title">
          <img src="edge-ai-title.svg" alt="ACM India Winter School on Edge AI">
        </div>
        **28 December 2025 to 4 January 2026**<br><br>

        **Venue:** CDS building, Indian Institute of Science (IISc), Bengaluru<br><br>

        <div style="margin-top: 10px; text-align: center;">
          <img src="IISc_logo1.png" 
               alt="ACM India Logo" 
               style="max-height: 250px; max-width: 120%; display: inline-block;">
        </div>        

    design:
      columns: 1
      css_class: "light"
      background:
        color: "white"
        image:
          filename: bg-iisc4-min.png
          size: contain
          mobile_size: contain
          position: "top left"
          anchor_y: top
          repeat: no-repeat
          filters:
            brightness: 0.5
        parallax: false   

    
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
      columns: 1
      spacing:
        padding: ["6rem","0","6rem","0"]

  # === 3. TOPICS BLOCK (Visually interactive with icons) ===
  - block: features
    id: topics
    content:
      title: Key Topics
      text: |
        The winter school covers foundational and advanced aspects of Edge AI.
      items:
        - name: Foundations of IoT, Accelerated Edge Computing and Edge AI
          icon: server
        - name: Tiny and Embedded Machine Learning
          icon: computer-desktop
        - name: Model Optimization and Acceleration for Edge AI
          icon: arrow-up-circle
        - name: Edge AI Platforms, Frameworks, and Deployment Pipelines
          icon: code-bracket
        - name: Federated Learning and Distributed Training for Edge Devices
          icon: users
        - name: Neuromorphic Computing and Brain-Inspired Architectures
          icon: cube
        - name: Generative AI and LLM at the Edge
          icon: sparkles
        - name: Agentic AI on the Edge
          icon: cog
        - name: Security, Privacy, and Responsible AI in Edge Systems
          icon: lock-closed
        - name: Benchmarking, Profiling, and Performance Evaluation of Edge AI Systems
          icon: chart-bar
        - name: Edge AI for Drones/UAVs, IoT, Smart Cities, and Industrial Applications
          icon: globe-alt
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
      columns: 3

  # === 4. SPEAKERS BLOCK (3-COLUMN GRID WITH VERTICAL SPACING, WIDTH OVERRIDDEN VIA CUSTOM CSS) ===
  - block: features
    id: speakers
    content:
      title: Speakers
      text: |
        ### **Keynote Speakers**
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1200px; margin: 0 auto;">
        
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;"> 
          <a href="https://edge.seas.harvard.edu/people/vijay-janapa-reddi">
            <img src="speaker_vijay.jpg" alt="Photo of Vijay Janappa Reddi" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Vijay Janappa Reddi</strong><br/>Harvard University</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://isc.mst.edu/people/ri/sdas/">
            <img src="speaker_sajal.jpg" alt="Photo of Sajal Das" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Sajal Das</strong><br/>Missouri Univ. of Sci. & Tech, USA</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://ojhavk.github.io/">
            <img src="speaker_varun.jpg" alt="Photo of Varun Ojha" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Varun Ojha</strong><br/>New Castle University, UK</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://sites.google.com/view/archan-misra">
            <img src="speaker_archan.jpg" alt="Photo of Archan Misra" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Archan Misra</strong><br/>SMU</p>
        </div>
  
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;"> 
          <a href="https://prakadambi.github.io/">
            <img src="speaker_prashanti.jpeg" alt="Photo of Prashanti" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Prashanti</strong><br/>AMD</p>
        </div>
  
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://sites.google.com/site/prasantmisra/">
            <img src="speaker_prasant.jpg" alt="Photo of Prasant Misra" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Prasant Misra</strong><br/>TCS Research</p>
        </div>
  
        </div>
        
        ### **Session Speakers**
  
        <div style="display: flex; flex-wrap: wrap; justify-content: center; text-align: center; max-width: 1200px; margin: 0 auto;">

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://iitbhu.ac.in/dept/cse/people/ajaycse">
            <img src="speaker_ajay.jpg" alt="Photo of Ajay Pratap" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Ajay Pratap</strong><br/>IIT Bhuvaneswar</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;"> 
          <a href="https://www.iitdh.ac.in/user-profile/gayathri-ananthanarayanan">
            <img src="speaker_gayathri.jpg" alt="Photo of Gayathri Ananthanarayanan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Gayathri Ananthanarayanan</strong><br/>IIT Dharwad</p>
        </div>

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://www.bits-pilani.ac.in/hyderabad/manik-gupta">
            <img src="speaker_manik.jpg" alt="Photo of Manik Gupta" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Manik Gupta</strong><br/>BITS Pilani</p>
        </div>
  
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://www.samy101.com/">
            <img src="speaker_pandarasamy.jpg" alt="Photo of Pandarasamy Arjunan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Pandarasamy Arjunan</strong><br/>IISc</p>
        </div>
  
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://cds.iisc.ac.in/faculty/simmhan/">
            <img src="speaker_yogesh.jpg" alt="Photo of Yogesh Simmhan" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Yogesh Simmhan</strong><br/>IISc</p>
        </div>
  
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://www.punitrathore.com/home">
            <img src="speaker_punit.jpg" alt="Photo of Punit Rathore" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Punit Rathore</strong><br/>IISc</p>
        </div> 

        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://eecs.iisc.ac.in/people/chetan-singh-thakur/">
            <img src="speaker_chetan.jpg" alt="Photo of Chetan Singh Takur" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Chetan Singh Takur</strong><br/>IISc</p>
        </div>
  
        <div style="width: 30%; min-width: 180px; margin: 40px 10px;">
          <a href="https://www.csa.iisc.ac.in/~skmandal">
            <img src="speaker_sumit.jpg" alt="Photo of Sumit Kumar Mandal" style="width: 100%; height: auto; border-radius: 50%; aspect-ratio: 1/1; object-fit: cover; border: 3px solid #0056b3;">
          </a>
          <p><strong>Sumit Kumar Mandal</strong><br/>IISc</p>
        </div>

        </div>
        
    design:
      view: compact
      columns: 1

# === 5. PROGRAMS (NEW SECTION) ===  
  - block: features
    id: program
    content:
      title: 📅 Program
      text: |
        <h3><strong>Session Legend</strong></h3>        
        <table class="schedule-table" 
               style="border-collapse: collapse; width: 100%; max-width: 650px; margin: 0 auto; 
                      text-align: left; border: 1px solid #ccc; border-radius: 10px; overflow: hidden;">
        <tbody>
        <tr>
        <td style="padding: 16px; line-height: 1.8;">        
          <span style="background-color:#F5F7F8; padding:4px 10px; border-radius:4px; margin-right:6px;">Break / Meal</span><br>        
          <span style="background-color:#F7E8FF; padding:4px 10px; border-radius:4px; margin-right:6px;">Keynote / Plenary / Invited Talk</span><br>        
          <span style="background-color:#E8F1FF; padding:4px 10px; border-radius:4px; margin-right:6px;">Lecture / Hands-on</span><br>        
          <span style="background-color:#FFF3E8; padding:4px 10px; border-radius:4px; margin-right:6px;">Lab / Tutorial</span><br>        
          <span style="background-color:#DE9F32; padding:4px 10px; border-radius:4px; margin-right:6px;">Industry Session</span><br>        
          <span style="background-color:#E6F5E6; padding:4px 10px; border-radius:4px; margin-right:6px;">Hackathon</span><br>        
          <span style="background-color:#CCF4B1; padding:4px 10px; border-radius:4px; margin-right:6px;">Closing Ceremony</span>        
        </td>
        </tr>
        </tbody>
        </table>        
        <br><br>      
        <h3><strong>Day 1 – 28th Dec 2025</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">8:00 – 9:00 AM</td><td colspan="2" style="padding:8px; text-align:center;">Breakfast</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Vijay Janappa Reddi (Harvard University)</td><td style="padding:8px;">Keynote Address</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Chetan Singh Takur (IISc)</td><td style="padding:8px;">Technical Talk</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Chetan Singh Takur (IISc)</td><td style="padding:8px;">Hands-on Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML Lab</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Tiny ML Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">7:00 – 8:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Dinner / Social</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 2 – 29th Dec 2025</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">8:00 – 9:00 AM</td><td colspan="2" style="padding:8px; text-align:center;">Breakfast</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Sumit Kumar Mandal (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Gayathri Ananthanarayanan (IIT Dharwad)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Gayathri Ananthanarayanan (IIT Dharwad)</td><td style="padding:8px;">Hands-on Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision Lab</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Embedded Computer Vision Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">7:00 – 8:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Dinner / Social</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 3 – 30th Dec 2025</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">8:00 – 9:00 AM</td><td colspan="2" style="padding:8px; text-align:center;">Breakfast</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Prashanti (AMD)</td><td style="padding:8px;">Invited Talk</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators Lab</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">ML on Edge Accelerators Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">7:00 – 8:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Dinner / Social</td></tr>
        </tbody></table>
        <br><br>   
        <h3><strong>Day 4 – 31st Dec 2025</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">8:00 – 9:00 AM</td><td colspan="2" style="padding:8px; text-align:center;">Breakfast</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">FL on Edge Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Varun Ojha (New Castle)</td><td style="padding:8px;">Invited Talk</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Varun Ojha (New Castle)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Yogesh Simmhan (IISc)</td><td style="padding:8px;">FL on Edge Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">7:00 – 8:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Dinner / Social (New Year's Eve)</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 5 – 1st Jan 2026</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">8:00 – 9:00 AM</td><td colspan="2" style="padding:8px; text-align:center;">Breakfast</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Sumit Kumar Mandal (IISc)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Prasant Misra (IISc & TCS)</td><td style="padding:8px;">Invited Talk</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Punit Rathore (IISc)</td><td style="padding:8px;">Hands-on Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Gen AI at Edge Lab</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">Pandarasamy Arjunan (IISc)</td><td style="padding:8px;">Gen AI at Edge Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">7:00 – 8:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Dinner / Social</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 6 – 2nd Jan 2026</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">8:00 – 9:00 AM</td><td colspan="2" style="padding:8px; text-align:center;">Breakfast</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Sajal Das (Missouri)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#FFF3E8;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">Manik Gupta (BITS, Pilani)</td><td style="padding:8px;">IoT Analytics Lab</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#DE9F32;"><td style="padding:8px;">4:00 – 5:30 PM</td><td style="padding:8px;">—</td><td style="padding:8px;">MATLAB Session</td></tr>
        <tr style="background-color:#DE9F32;"><td style="padding:8px;">5:30 – 7:00 PM</td><td style="padding:8px;">—</td><td style="padding:8px;">Reserved (Qualcomm Session)</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">7:00 – 8:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Dinner / Social</td></tr>
        </tbody></table>
        <br><br>
        <h3><strong>Day 7 – 3rd Jan 2026</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">8:00 – 9:00 AM</td><td colspan="2" style="padding:8px; text-align:center;">Breakfast</td></tr>
        <tr style="background-color:#F7E8FF;"><td style="padding:8px;">9:00 – 10:00 AM</td><td style="padding:8px;">Archan Misra (SMU)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">10:00 – 11:00 AM</td><td style="padding:8px;">Ajay Pratap (IIT Bhu)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">11:00 – 11:15 AM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E8F1FF;"><td style="padding:8px;">11:15 – 12:45 PM</td><td style="padding:8px;">Ajay Pratap (IIT Bhu)</td><td style="padding:8px;">Technical Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">12:45 – 2:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Lunch Break</td></tr>
        <tr style="background-color:#DE9F32;"><td style="padding:8px;">2:00 – 3:30 PM</td><td style="padding:8px;">—</td><td style="padding:8px;">Arm Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">3:30 – 4:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Tea/Coffee Break</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">4:00 – 5:30 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Work Session</td></tr>
        <tr style="background-color:#E6F5E6;"><td style="padding:8px;">5:30 – 7:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Hackathon Work Session</td></tr>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">7:00 – 8:00 PM</td><td colspan="2" style="padding:8px; text-align:center;">Dinner / Social</td></tr>
        </tbody></table>
        <br><br>      
        <h3><strong>Day 8 – 4th Jan 2026</strong></h3>
        <table class="schedule-table" style="border-collapse: collapse; width: 100%; text-align: left;">
        <thead><tr style="background-color:#ddd;"><th style="padding:8px;">Time</th><th style="padding:8px;">Speaker</th><th style="padding:8px;">Title</th></tr></thead>
        <tbody>
        <tr style="background-color:#F5F7F8;"><td style="padding:8px;">8:00 – 9:00 AM</td><td colspan="2" style="padding:8px; text-align:center;">Breakfast</td></tr>      
        <tr style="background-color:#E6F5E6;">
        <td style="padding:8px;">9:00 AM – 12:45 PM</td>
        <td colspan="2" style="padding:8px; text-align:center;">Hackathon Work Session</td>
        </tr>      
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
      css_class: "bg-gray-100 dark:bg-gray-900"
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]

# === 6. LOGISTICS AND MAPS (NEW SECTION) ===
  - block: markdown
    id: venue
    content:
      title: Venue
      text: |
        This Program is hosted at the **CDS building, Indian Institute of Science (IISc), Bengaluru**.
        
        ### Location and Access
        * **Location:** The IISc campus is easily accessible from all parts of Bengaluru. The nearest metro station is **Yeshwanthpur**.
        * **Venue Map:** The CDS building is located near the main administrative block. <a href="https://maps.app.goo.gl/Sygki6ResDbrqMEy9">
          <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="location-dot" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" data-fa-i2svg="" style="display: inline-block; height: 1em; margin-left: 0.5em;"><path fill="currentColor" d="M168.3 499.2C116.1 435 0 279.4 0 192C0 85.96 85.96 0 192 0C298 0 384 85.96 384 192C384 279.4 267 435 215.7 499.2C203.4 514.5 180.6 514.5 168.3 499.2H168.3zM192 256C227.3 256 256 227.3 256 192C256 156.7 227.3 128 192 128C156.7 128 128 156.7 128 192C128 227.3 156.7 256 192 256z"></path></svg> Click Here
          </a>
        
        ### Key Contacts
        
        If you have any logistical or academic questions regarding the Winter School, please contact the coordinators:
        * **Pandarasamy Arjunan:** <a href="mailto:samy@iisc.ac.in">samy@iisc.ac.in</a>
        * **Yogesh Simmhan:** <a href="mailto:simmhan@iisc.ac.in">simmhan@iisc.ac.in</a>
        
    design:
      columns: 1
      css_class: "" 
      background:
        color: white
      spacing:
        padding: ["6rem","0","6rem","0"]

  # === 7. SPONSORS / SUPPORTED BY (NEW SECTION WITH LOGOS) ===
  - block: markdown
    id: sponsors
    content:
      title: Supported By
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
